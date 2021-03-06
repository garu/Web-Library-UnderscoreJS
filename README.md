# NAME

Web::Library::UnderscoreJS - Distribution wrapper around UnderscoreJS

# SYNOPSIS

    my $library_manager = Web::Library->instance;
    $library_manager->mount_library({ name => 'UnderscoreJS' });

# DESCRIPTION

This is a distribution wrapper around Underscore.js. It enables you to include
the client-side library in multiple Web application projects with very little
effort. See [Web::Library](https://metacpan.org/pod/Web::Library) for the general concept and how to use it with
[Catalyst](https://metacpan.org/pod/Catalyst).

# LIBRARY VERSIONS

The following versions are available. For each version all included files are
listed. Files marked with an asterisk are included in that versions' asset
list - see [Web::Library](https://metacpan.org/pod/Web::Library)'s `css_link_tags_for()` and `script_tags_for()`
methods for an explanation of the concept.

- Version 1.4.4
=item Version 1.5.0
=item Version 1.5.1
=item Version 1.5.2 (the default)

        * js/underscore-min.js

# LIBRARY WEBSITE

Underscore.js can be found at [http://underscorejs.org/](http://underscorejs.org/).

# AUTHORS

The following person is the author of all the files provided in
this distribution EXCEPT Underscore.js files found in `share/`.

Marcel Gruenauer `<marcel@cpan.org>`, [http://marcelgruenauer.com](http://marcelgruenauer.com)

# COPYRIGHT AND LICENSE

Underscore.js is licensed under the MIT license.

The following copyright notice applies to all files provided in this
distribution EXCEPT Underscore.js files found in `share/`.

This software is copyright (c) 2013 by Marcel Gruenauer.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
