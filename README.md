# ActionFPS Blacklist

[Edit the blacklist](https://github.com/ActionFPS/blacklist/edit/master/serverblacklist.cfg)

# Onboarding steps

1. Request user for GitHub ID
2. Add user to [Ladder Cops Team](https://github.com/orgs/ActionFPS/teams/ladder-cops/) or add a [Collaborator](https://github.com/ActionFPS/blacklist/settings/collaboration).
3. User accepts the invitation.
4. Now user can [Edit the blacklist](https://github.com/ActionFPS/blacklist/edit/master/serverblacklist.cfg) directly.

# Frequently Asked Questions

Put them here for future reference.

## What information to add in blacklist?
Name, date, reason, ip. Then add text like this:
-  // Name: unarmed
-  // Ban date: 2017-04-16
-  // Ban reason: fly hack & teleport
-  11.22.33.44
  
  Then save. Add banned names in commit changes.
  
## How long does it take to reload the blacklist?

At most one minute (server re-reads the blacklist every minute) + time taken to update the file (which is immediate)
