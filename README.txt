= ohmygems

home :: https://github.com/seattlerb/ohmygems
rdoc :: http://docs.seattlerb.org/ohmygems

== DESCRIPTION:

I'm tired of the complications that tools like bundler and rvm inject
into my system and my workflow. I don't want 4 billion gems installed
globally. I don't want to have `rake` slow down for no good reason. I
don't want rvm to regress on undefined variables over and over and
over (and I don't want to report it anymore when it does). I want as
much simplicity as I can afford and still be able to get my job done.

I've found pretty good balance using rbenv (only when needed) and by
using this 45 line shell function `ohmygems` (aliased to `omg`, of
course).

I still have my system-level gems as my previous GEM_HOME gets moved
into GEM_PATH so things like minitest and autotest are always
available. But now I have private gems that are incredibly easy to
switch around and only rely on simple environment variables to manage.

To go back to normal, simply run `omg reset`.

== FEATURES/PROBLEMS:

* FIX (list of features or problems)

== SYNOPSIS:

  % cd newproject
  % omg newproject
  % gem i bundler
  % bundle

== REQUIREMENTS:

* bash (and probably zsh?)
* rubygems

== INSTALL:

* sudo gem install ohmygems
* Follow the post-install instruction to integrate into your shell.

== LICENSE:

(The MIT License)

Copyright (c) Ryan Davis, seattle.rb

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
