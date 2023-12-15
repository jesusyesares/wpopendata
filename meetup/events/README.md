# WPOpenData - Meetup Events

## Formats

- [CSV](meetup_events.csv)
- [JSON](meetup_events.json)

## Fields

- [`meetup_id`](/meetup/groups/): (int) Meetup.com Group ID.
- `meetup_event_id`: (int) Meetup.com Event ID.
- `meetup_event_name`: (string) Event title.
- `meetup_event_link`: (string) Meetup.com Event URL.
- `meetup_event_utc`: (int) Event UNIX time UTC.
- `meetup_event_date`: (date) Event date (local time).
- `meetup_event_time`: (time) Event time (local time).
- `meetup_event_duration`: (int) Event duration (seconds).
- `meetup_event_tz`: (string) Event TimeZone
- `meetup_event_online`: (bool) Is the event online?
- `meetup_event_cancelled`: (bool) Is the event cancelled?
- `meetup_event_rsvp`: (int) RSVP, Attendees.
- `meetup_event_active`: (bool) Is the event active?
- `venue_name`: (string) Venue name.
- `venue_address`: (string) Venue address.
- `venue_city`: (string) Venue city.
- `venue_country_id`: [`country_id`](/country/) (string) ISO 3166 codes.
- `venue_lat`: (float) Venue latitude.
- `venue_lon`: (float) Venue longitude.

## Sources

- [Meetup.com](https://www.meetup.com/)