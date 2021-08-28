I got up until the point before the Part 2 section.

Connected with Flatiron TC.

We did find a similar report on StackOverflow.

Unfortunately this remains unresolved. Error message below:

Here was the error message:

Traceback (most recent call last):
37: from bin/rails:3:in `<main>' 36: from bin/rails:3:in `load'
35: from /Users/lesliegonzalez/Development/code/devise_lab/bin/spring:15:in `<top (required)>' 34: from /Users/lesliegonzalez/Development/code/devise_lab/bin/spring:15:in `require'
33: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/spring-2.1.1/lib/spring/binstub.rb:11:in `<top (required)>' 32: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/spring-2.1.1/lib/spring/binstub.rb:11:in `load'
31: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/spring-2.1.1/bin/spring:49:in `<top (required)>' 30: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/spring-2.1.1/lib/spring/client.rb:30:in `run'
29: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/spring-2.1.1/lib/spring/client/command.rb:7:in `call' 28: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/spring-2.1.1/lib/spring/client/rails.rb:28:in `call'
27: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/spring-2.1.1/lib/spring/client/rails.rb:28:in `load' 26: from /Users/lesliegonzalez/Development/code/devise_lab/bin/rails:9:in `<top (required)>'
25: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/bootsnap-1.8.1/lib/bootsnap/load_path_cache/core_ext/kernel_require.rb:31:in `require' 24: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/bootsnap-1.8.1/lib/bootsnap/load_path_cache/core_ext/kernel_require.rb:22:in `require_with_bootsnap_lfi'
23: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/bootsnap-1.8.1/lib/bootsnap/load_path_cache/loaded_features_index.rb:92:in `register' 22: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/bootsnap-1.8.1/lib/bootsnap/load_path_cache/core_ext/kernel_require.rb:23:in `block in require_with_bootsnap_lfi'
21: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/bootsnap-1.8.1/lib/bootsnap/load_path_cache/core_ext/kernel_require.rb:23:in `require' 20: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/railties-5.2.6/lib/rails/commands.rb:18:in `<main>'
19: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/railties-5.2.6/lib/rails/command.rb:46:in `invoke' 18: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/railties-5.2.6/lib/rails/command/base.rb:69:in `perform'
17: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/thor-1.1.0/lib/thor.rb:392:in `dispatch' 16: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/thor-1.1.0/lib/thor/invocation.rb:127:in `invoke_command'
15: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/thor-1.1.0/lib/thor/command.rb:27:in `run' 14: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/railties-5.2.6/lib/rails/commands/server/server_command.rb:142:in `perform'
13: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/railties-5.2.6/lib/rails/commands/server/server_command.rb:142:in `tap' 12: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/railties-5.2.6/lib/rails/commands/server/server_command.rb:147:in `block in perform'
11: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/railties-5.2.6/lib/rails/commands/server/server_command.rb:53:in `start' 10: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/rack-2.2.3/lib/rack/server.rb:327:in `start'
9: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/thin-1.8.1/lib/rack/handler/thin.rb:22:in `run' 8: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/thin-1.8.1/lib/thin/server.rb:162:in `start'
7: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/thin-1.8.1/lib/thin/backends/base.rb:75:in `start' 6: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/eventmachine-1.2.7/lib/eventmachine.rb:195:in `run'
5: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/eventmachine-1.2.7/lib/eventmachine.rb:195:in `run_machine' 4: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/thin-1.8.1/lib/thin/backends/base.rb:65:in `block in start'
3: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/thin-1.8.1/lib/thin/backends/unix_server.rb:19:in `connect' 2: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/eventmachine-1.2.7/lib/eventmachine.rb:562:in `start_unix_domain_server'
1: from /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/eventmachine-1.2.7/lib/eventmachine.rb:533:in `start_server' /Users/lesliegonzalez/.rvm/gems/ruby-2.6.1/gems/eventmachine-1.2.7/lib/eventmachine.rb:533:in `start_unix_server': no unix-domain acceptor (RuntimeError)
