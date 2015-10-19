# Prompt

### What is a good Prompt do

* Display the current user name
* Display the current host
* Display the current directory
* Display the current shell
* Display the current coding branch


### What is a good looks like
![for example](resource/img/Capture.png)


* Case Cmd (Windows)

    By default, cmd.exe didn't support display embedded color by a escape sequence of characters.
    Here is a extension tool called ["ANSICON"](https://github.com/adoxa/ansicon), it provides ANSI escape sequence recognition for Windows console programs (both 32- (x86) and 64-bit (x64)). It is basically the Windows equivalent of ANSI.SYS.

* Case PowerShell (Windows)

* Case Oh-my-zsh
    Just append this bellowing configuration in to your zsh configuration file ".zshrc" 
    
'''PowerShell
    PROMPT='%{$fg_bold[green]%}%n@%m %{$fg_bold[red]%}in %{$fg_bold[green]%}%p%{$fg[cyan]%}%d
    %{$fg_bold[blue]%}$(git_prompt_info)%{$fg_bold[blue]%}% %{$reset_color%}%% '
'''

* Case Bash (\*nix|msys|cygwin)



[A better PROMPT for cmd.exe or Cool Prompt Environment Variables and a nice transparent multi-prompt](http://www.hanselman.com/blog/ABetterPROMPTForCMDEXEOrCoolPromptEnvironmentVariablesAndANiceTransparentMultiprompt.aspx)
