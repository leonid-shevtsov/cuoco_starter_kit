set :stage_dir, 'stages'
set :default_stage, 'vagrant'
require 'capistrano/ext/multistage'

ssh_options[:forward_agent] = true
default_run_options[:pty] = true

set :chef_path, 'chef'
set :chef_install_command, 'wget -q -O - https://raw.github.com/gist/3601146/install_chef_ubuntu_precise.sh | sudo bash'
require 'cuoco/capistrano/automatic'
