# Moodle Team Profiles block
This plugin adds a new block type for Moodle. Its aim is to let site staff manage an "About the team" style profile list (photo + bio) through a simple admin screen, instead of hand-editing HTML that can easily break.
## Features
- Site-wide team member list (name, bio, photo)
- Reordering 
- Show/hide members
- Photo upload via Moodle's file picker
- Four ready-made layouts: designs chosen by researching team sections used across professional and agency sites
- Layouts are via mustache templates, that can be overriden in the theme
- No HTML editing required to update content
## Installation
1. Copy (or clone) this repository into `blocks/team_profiles` in your Moodle installation.
2. Visit **Site administration → Notifications** to complete the install.
3. Add the **Team Profiles** block to any page.
## Usage
1. Add the block to a page (e.g. the front page or dashboard).
2. Click **Manage team members** in the block footer.
3. Add members with a name, bio, and photo.
4. Use the up/down arrows to set display order.
   Team members are shared site-wide — updating them from any instance of the block updates what every instance displays.
### Adding to the Dashboard
If you add this block to the **Dashboard**, make sure you add it via **Site administration → Appearance → Default Dashboard page**, not from your own personal Dashboard. This ensures it is pushed out to everyone.
## Requirements
- Moodle 4.0 or later
## License
GPL v3 or later
