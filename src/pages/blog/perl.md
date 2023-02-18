---
layout: '../../layouts/Post.astro'
title: Perl
image: /images/perl
publishedAt: "2023-02-08"
category: 'languages'
---

## [`Perl`](https://www.perl.org)
> Perl is a highly capable, feature-rich programming language with over 30 years of development.

### [`strict`](https://perldoc.perl.org/strict)
Pragma to restrict unsafe constructs

```perl
use strict;
```

### [`warnings`](https://perldoc.perl.org/warnings)
Pragma to control optional warnings

```perl
use warnings;
```

### Scalars

Declare scalar
```perl
my $availableName = "";
```

Compare strings
```perl
if ($availableName eq $lastResult) {
  $continueProcessing = 1;
}
```

[`chomp`](https://perldoc.perl.org/functions/chomp)

Remove newlines

```perl
chomp $firstname;
```


### Arrays

Read array from `STDIN`
```perl
my @firstnames = <STDIN>;
```

Copy array (TODO dive into deep copy)
```perl
my @lastnames = @firstnames;
```

Initialize array
```perl
my @names = ();
```

[Iterate through an array](https://www.perl.com/article/perl-foreach-loops/)
```perl
foreach $firstname (@firstnames) {
  # Do something
}
```

[Sort an array](https://perlmaven.com/sorting-arrays-in-perl)
```perl
@sortednames = sort { $a cmp $b } @names;
```

Execute a shell command and capture the results into an array
```perl
my @results = `nslookup $tryname.com`
```

[Read off the front of an array](https://perlmaven.com/manipulating-perl-arrays)
```perl
my $foundString = shift @results;
```

[Print an array, adding newlines](https://stackoverflow.com/questions/1863943/how-can-i-print-list-elements-separated-by-line-feeds-in-perl)
```perl
print "$_\n" for @resortednames;
```

### [Regular Expressions (Regex)](https://perldoc.perl.org/perlre)

Match a value within a string
```perl
my $isAvailable = ($foundString =~ m/server can/);
```

### [Hashes](https://www.perl.com/article/27/2013/6/16/Perl-hash-basics-create-update-loop-delete-and-sort/)

Declare a hash
```perl
my %resultshash = ();
```

Assign a hash value
```perl
$resultshash{$result} = 1;
```

### File handles

Print to `STDERR`
```perl
print STDERR "$foundString\n";
```

[Open a file in read mode](https://www.perltutorial.org/perl-open-file/)
```perl
open(FH, '<', 'data') or die $!;
```
or
```perl
open my $fh, '<', 'data' or die $!;
```

[Open a new file in write mode](https://www.perltutorial.org/perl-open-file/)
```perl
open(FH, '>', 'data') or die $!;
```
or
```perl
open my $fh, '>', 'data' or die $!;
```

[Open a new file in append mode](https://www.perltutorial.org/perl-open-file/)
```perl
open(FH, '>>', 'data') or die $!;
```
or
```perl
open my $fh, '>>', 'data' or die $!;
```

[Close the file](https://www.perltutorial.org/perl-open-file/)
```perl
close(FH);
```
or
```perl
close $fh;
```

### [`usleep`](https://perldoc.perl.org/Time::HiRes)

Sleep in microseconds

```perl
use Time::HiRes qw(usleep);

# Sleep for 50 miliseconds
usleep(50000);
```

[See also](https://stackoverflow.com/questions/896904/how-do-i-sleep-for-a-millisecond-in-perl)

### Modules

#### [`Net::DNS`](https://metacpan.org/pod/Net::DNS)
[Examples](https://metacpan.org/pod/Net::DNS#EXAMPLES)

### [`cpan`](http://www.cpan.org/modules/INSTALL.html)

Install cpanminus
```bash
brew install cpanminus
```
