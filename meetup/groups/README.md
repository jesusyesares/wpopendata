# WPOpenData - Meetup Groups

## Formats

- [CSV](meetup_groups.csv)
- [JSON](meetup_groups.json)

## Fields

- `meetup_id`: (int) Meetup.com Group ID.
- `meetup_slug`: (string) Meetup.com Group Slug.
- `meetup_name`: (string) Meetup.com Group name.
- `meetup_link`: (string) Meetup.com Group URL.
- [`country_id`](/country/): (string) ISO 3166 codes.
- `meetup_members`: (int) Group members.
- `meetup_date_created`: (date) Group creation date.
- `meetup_lat`: (float) Group city latitude.
- `meetup_lon`: (float) Group city longitude.
- `meetup_tz`: (string) Group TimeZone
- `meetup_active`: (bool) Is the group active?

## Sources

- [Meetup.com](https://www.meetup.com/)