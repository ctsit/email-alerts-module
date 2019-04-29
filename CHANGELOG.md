# Change Log
All notable changes to the email_alerts project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).


## [2.1.80] - 2019-04-29
### Added
- Add logs when queue is deleted (bascome)
- New alert name field and PHP Mailer version (bascome)
- Add new documentation (bascome)
- Add a conditional for the scheduled $project_id to ensure it is not empty (bascome)
- Add vanderbilt_emailTrigger on queued emails by directory_prefix (bascome)
- Add parentheses for hasQueueExpired. (bascome)

### Changed
- Move delayModuleExecution to the beginning of sendEmailAlert (Philip Chase)
- Fix for add survey link (bascome)
- Preview record get data by specified record (bascome)
- Bug fix. (bascome)
- Updated PHPMailer in Preview Record (bascome)
- Show alert name on update values (bascome)
- Change directory_prefix for 'email_alerts' (bascome)


## [ctsit-2.1.3] - 2019-01-10
### Changed
- Add Changelog (Philip Chase)
- Move delayModuleExecution to the beginning of sendEmailAlert (Philip Chase)
- Enable debug messages in Mailer (bascome)
- Remove empty references from isAlreadyInQueue (bascome)


## [2.1.2] - 2018-11-29
### Summary
- Previous release

