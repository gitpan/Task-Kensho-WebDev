# NAME

Task::Kensho::WebDev - A Glimpse at an Enlightened Perl: Web Development

# VERSION

version 0.35

# SYNOPSIS

    > cpanm --interactive Task::Kensho::WebDev

# DESCRIPTION

From [http://en.wikipedia.org/wiki/Kensho](http://en.wikipedia.org/wiki/Kensho):

> Kenshō (見性) (C. Wu) is a Japanese term for enlightenment
> experiences - most commonly used within the confines of Zen
> Buddhism - literally meaning "seeing one's nature"\[1\] or "true
> self."\[2\] It generally "refers to the realization of nonduality of
> subject and object."\[3\]

[Task::Kensho](https://metacpan.org/pod/Task::Kensho) is a first cut at building a list of recommended modules
for Enlightened Perl development. CPAN is wonderful, but there are too
many wheels and you have to pick and choose amongst the various
competing technologies.

The plan is for [Task::Kensho](https://metacpan.org/pod/Task::Kensho) to be a rough testing ground for ideas that
go into among other things the Enlightened Perl Organisation Extended
Core (EPO-EC).

The modules that are bundled by [Task::Kensho](https://metacpan.org/pod/Task::Kensho) are broken down into
several categories and are still being considered. They are all taken
from various top 100 most used perl modules lists and from discussions
with various subject matter experts in the Perl Community. That said,
this bundle does _not_ follow the guidelines established for the EPO-EC
for peer review via industry advisers.

Starting in 2011, [Task::Kensho](https://metacpan.org/pod/Task::Kensho) split its sub-groups of modules into
individually-installable tasks.  Each [Task::Kensho](https://metacpan.org/pod/Task::Kensho) sub-task is listed at the
beginning of its section in this documentation.

When installing [Task::Kensho](https://metacpan.org/pod/Task::Kensho) itself, you will be asked to install each
sub-task in turn, or you can install individual tasks separately. These
individual tasks will always install all their modules by default. This
facilitates the ease and simplicity the distribution aims to achieve.

# RECOMMENDED MODULES

## [Task::Kensho::WebDev](https://metacpan.org/pod/Task::Kensho::WebDev): Web Development

### [CGI::FormBuilder::Source::Perl](https://metacpan.org/pod/CGI::FormBuilder::Source::Perl)

Build CGI::FormBuilder configs from Perl syntax files.

### [Dancer](https://metacpan.org/pod/Dancer)

A lightweight yet powerful web application framework

### [MIME::Types](https://metacpan.org/pod/MIME::Types)

Definition of MIME types

### [Mojolicious](https://metacpan.org/pod/Mojolicious)

Real-time web framework

### [Plack](https://metacpan.org/pod/Plack)

Flexible superglue between Web Servers and Perl Web Frameworks or code.

### [Task::Catalyst](https://metacpan.org/pod/Task::Catalyst)

Catalyst is The Elegant MVC Web Application Framework. Task::Catalyst is all you need to start with Catalyst.

### [Template::Toolkit](https://metacpan.org/pod/Template::Toolkit)

Template Processing System

### [XML::Atom](https://metacpan.org/pod/XML::Atom)

Atom feed and API implementation

### [XML::RSS](https://metacpan.org/pod/XML::RSS)

Creates and updates RSS files

# INSTALLING

Since version 0.34, [Task::Kensho](https://metacpan.org/pod/Task::Kensho) has made use of the `optional_features` field
in distribution metadata. This allows CPAN clients to interact with you
regarding which modules you wish to install.

The `cpanm` client requires interactive mode to be enabled for this to work:

    cpanm --interactive Task-Kensho

# BUGS AND LIMITATIONS

This list is by no means comprehensive of the "Good" Modules on CPAN.
Nor is this necessarily the correct path for all developers. Each of
these modules has a perfectly acceptable replacement that may work
better for you. This is however a path to good perl practice, and a
starting place on the road to Enlightened Perl programming.

Please report any bugs or feature requests to
[https://github.com/EnlightenedPerlOrganisation/task-kensho/issues](https://github.com/EnlightenedPerlOrganisation/task-kensho/issues).

# SEE ALSO

[http://www.enlightenedperl.org/](http://www.enlightenedperl.org/),
[Perl::Dist::Strawberry](https://metacpan.org/pod/Perl::Dist::Strawberry)

# AUTHOR

Chris Prather <chris@prather.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2008 by Chris Prather.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
