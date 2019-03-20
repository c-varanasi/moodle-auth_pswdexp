# moodle-auth_pwdexp
Moodle password expiration check based on the original plugin by David Bezemer- https://github.com/DBezemer/moodle-auth_pwdexp.
Key modifications:
- Compatible with PHP7.
- Works with all authentication methods and not just manual.
- Default date is set to the expiration days setting rather than the date before today. 
- Does not expire the password right away when no settings are found. 
