# VeilX

**Create. Talk. Disappear.**

VeilX is a privacy-focused temporary chat platform for conversations that should not live forever.

Live at: **https://veilxmessenger.github.io/**

## First release

VeilX lets you:

- Create an anonymous identity without a phone number or email
- Create temporary chat rooms with expiration timers
- Give rooms names and optional passwords
- Share invite links or join with a room code
- Preview a room before joining
- Chat in real time through lightweight polling
- See room members and roles
- Manage members with owner and admin controls
- Install VeilX as a mobile-friendly PWA

## Privacy by design

- No phone numbers
- No email accounts
- No public profiles
- No permanent room history
- Rooms, members, and messages disappear when a room expires

For abuse prevention, VeilX records public IP addresses and request timestamps. One record is kept per IP with its first and most recent request. This information is restricted to the site owner.

## First-release limits

- Normal identities can have up to **3 active rooms**
- The site owner can create unlimited active rooms
- Room creation has a **5-second cooldown**
- One identity registration is allowed per public IP address

## Room roles

- **Owner:** controls the room and can manage administrators
- **Admin:** can help moderate room members
- **Member:** participates in the conversation

## Security note

VeilX is an early release. Do not use it for highly sensitive information until it has received a full independent security review.

## Project status

This is the first public release of VeilX. The project is focused on temporary, anonymous, private conversations—not social networking or permanent messaging.

## Links

- Website: https://veilxmessenger.github.io/
- Release announcement: [TELEGRAM_RELEASE.md](TELEGRAM_RELEASE.md)

## License

Add the project license before public distribution.
