# aws-credentials-manager

Utility for managing multiple AWS credentials files.

Need more than one `~/.aws/credentials` file. If so, you're at the right place.

```shell
➜ ./awscm        

Credentials Manager for AWS (v1.0.0)

Usage
  ls                     list settings
  current                show the current settings
  use <settings>         switch to <settings>
  create <settings>      create/edit <settings>
  rm <settings>          remove the <settings>
  edit <settings>        create/edit <settings>
  help                   show this message
  ```
  
  ## FAQ
  **Q**: I use tools that automatically modify `~/.aws/credentials`. How can I keep them from modifying settings?
  
  **A**: Navigate to `~/.aws_creds_man` and set the setting files you do not want modified to readonly i.e. `chmod 400 ~/.aws_creds_man/my_settings` 

## License
MIT
