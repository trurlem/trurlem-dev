Ansible Role - dotfiles
=========

A role for automating dotfiles deployment.


Role Variables
--------------

| Variable | Meaning |
|--|--|
| git_files| List of git configuration files|
| git_path | Path to folder containing git configuration files in dotfiles repo|
| host_home | Dofiles will be deployed here|
| host_repo_path | Location on the host where the dotfiles repo should be cloned |
| host_zsh_custom_path | Path on the host where zsh customization is deployed |
| repo | URL pointing to the dotfiles repo |
| repo_accept_hostkey | `accept_hostkey` used when cloning the dotfiles repo|
| repo_branch | Branch of the dotfiles repo to be cloned|
| zsh_custom_plugin_files| List of zsh custom plugin files |
| zsh_custom_plugins_path| Path to folder containing plugin files in the dotfiles repo |
| zsh_custom_theme_files| List of zsh custom theme files |
| zsh_custom_themes_path| Path to folder containing theme files in the dotfiles repo |
| zsh_override_files| List of zsh override files |
| zsh_overrides_path| Path to folder containing override files in the dotfiles repo|

See `defaults/main.yml` for default values.
