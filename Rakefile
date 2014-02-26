# -*- ruby -*-

require "rubygems"
require "hoe"

Hoe.plugin :seattlerb

Hoe.spec "ohmygems" do
  developer "Ryan Davis", "ryand-ruby@zenspider.com"

  license "MIT"

  self.version = "1.1.0"

  self.post_install_message = <<-"EOM"

    Add the following to your ~/.bashrc or equivalent:

      source $(gem env gemdir)/gems/ohmygems-#{self.version}/ohmygems

    If you are using chruby to manage rubies, also add:

      source $(gem env gemdir)/gems/ohmygems-#{self.version}/ohmygems_chruby

  EOM
end

# vim: syntax=ruby
