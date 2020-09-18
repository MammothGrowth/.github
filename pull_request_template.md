# New Pull Request

* Check off the things that are applicable.  
* Remove sections that are N/A
* **Some sections are mandatory for a review to continue.**


### What has changed?
- [ ] New Models
- [ ] Updated Models
- [ ] Config Change

### Complexity
- [ ] Simple 1-liner, please rubber stamp
- [ ] Simple model update.  I don't expect any issues
- [ ] Business rules.  Need another set of eyes.  I have provided detailed context and documentations on how rules are meant to function
- [ ] Massive re-write.  What have I done?

### What issue is this PR meant to fix? 
*Provide any context to assist the reviewer and a speedy PR turnaround:*
*Describe the bug/enhancement/request from a business perspective.  Ie:  Explain the problem*

- [ ] *NONE!  I do not want my PR to be reviewed!*

### Model Schemas
All of the following exist:
- [ ] Schema exist for the new/updated model
- [ ] An appropriate unique test exists in schema

If the above is not applicable specify why:
- [ ] No model changes
- [ ] other:

### Testing
I have done all:
- [ ] `dbt run` locally
- [ ] `dbt test` locally

or:
- [ ] It wasn't necessary because: 

### Deployment Plan

- [ ] There are no breaking changes.  I will merge as soon as approved.
- [ ] There are breaking changes.  My deploy plan is:

