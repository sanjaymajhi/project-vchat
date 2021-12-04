# Video conferencing webapp

## Homepage

- Host a meeting instantly (No Sign in required)
  - When clicked on host a meeting, a new meet is created instantly
- Join a meeting instantly (No Sign in required)
  - When clicked on join a meeting, a new popup shows, users can paste the meeting code and join meets.
- Login/Signup
  - Users can have access to premium features, such as create rooms, share rooms, manage previous chats, calender, themes etc.

## Dashboard

- Chat Rooms
  - Users can have multiple rooms, each rooms have their own ids.
  - A personal room for users to store their drafts/ important stuffs. Users can share these rooms.
  - A user can join/create multiple rooms.
  - Link sharing to easily allow multiple members join rooms.
  - Users have access to previous chats.
  - Easy bifurcation between senders and the user . Default alignment for remote sender is left while local user is right.
  - User can join room's meeting by a single click.
  - All the chats ie. meeting'chat and dashboard's chat are synced. Users can send/ recieve messages from the meet/dashboard both.
- Meetings
  - Schedule a meet: User can create meeting rooms, and share them. Each time user creates a room, he is by default added to the room.
  - Join a meet: Joins a meeting instantly.
- Settings
  - Contains custom settings for the navigation bar, theme switching, toggling of navigation bar.
- Logout

## Meet

- Video Call with multiple people support
- Admit/deny users
  - Any time a new user joins the meet, a request popups.
  - Admin could either admit or deny.
  - Tones whenever user joins (participants) or admit request popups (admin) .
- Video/audio on/off
- Video pinning /Muting other participants
  - Users can pin video/ mute participants.
- Screen sharing
- Recordings
  - Both video and screen could be recorded on a single click. Recorded files are stored locally.
- Chats
  - Users can chat with fellow participants once admitted.
  - Everytime a new message arrives, a tone and a batch is displayed.
- Meeting Link sharing
  - Participants could easily share meeting links.
- Real time Date/Time Update

- ### Implementation Details
  - Tech Stacks Used:
    - Socketio
    - WebRTC
    - Firebase ( for Database )
    - Node, express JS (Server)
    - HTML, CSS
