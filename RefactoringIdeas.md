

### Refactoring Ideas

- Use `git` for storing the incremental changes (just like CyberDojo does). 
- Use `gitter` to get notifications across all users across all problems...
  - You will need to use webhooks to connect up Gitter with CloudCoder
  - https://github.com/gitterHQ/services

### Phased approach 

To get Dynamic Support, we can take two step process:
  - send notifications whenever database is updated (just like you trigger emails)
  - replace Git as the storing method, that way "diff"s can be sent to Gitter directly
