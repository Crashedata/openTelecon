# openTelecon
An open source P2P video conferencing solution written in PHP, HTML5 and CSS3, and using webGL.
The goal of openTelecon is to create a modern video conferencing solution that runs entirely
within a web browser, without using flash, that also supports modern features.

An initial alpha release is planned by 12/1/17.

# Currently being worked on:
<ol>
<li>Core engine creation. This involves creating the core PHP scripts, and getting basic multi-person video conferencing (up to 10 simultaneous video streams) up and running.</li>
<li>Initial database creation. This involves creating the table structure, and initial database configurations.</li>
<li>Basic UI design. This involves creating the initial UI, which will be expanded upon in later releases. Must be user re-arangable, with both set layouts and the ability for users to create custom layouts. This also involves writing HTML5 and CSS3 to handle the design.</li>
<li>Chat system, with support for up to 100 participants, and support for direct messaging.</li>
<li>Basic whiteboard system, with support for multiple colors, multiple whiteboards, and whiteboard switching.</li>
<li>Login system.</li>
<li>Basic user-access rights system with access rights differing between admin/host/participant.</li>
</ol>
# Planned for future releases, but not currently being worked on:
<ol>
<li>Variable video compression and quality based on each invidual participants Internet speed.</li>
<li>Support for multiple "meeting room" instances on a single server.</li>
<li>Support for up to 64 simultaneous video streams.</li>
<li>Screen sharing support, with the ability to authorize another participant to control your screen, and drawing on screen support.</li>
<li>More advanced user-access rights system with access rights differing between admin/host/presenter/participant/attendee/bots/custom profiles.</li>
<li>HIPAA compliance so program can be safely used in medical environments, including in remote telemedicine.</li>
<li>Compiance with School Security standards so program can be safely used in educational environments, including as a virtual classroom tool.</li>
<li>Support for sharing and multi-user interaction on web apps, including those programmed in Unity game engine, and deployed for web use. This would also include web apps programmed in other environments.</li>
<li>Local client programmed in Python or another multi-platform language for users who's web browsers cannot run the web client. This would essentially be a custom web browser that could run the client, probably using either Firefox's or Chrome's rendering engine (WebKIT or Gecko).</li>
<li>File sharing support</li>
<li>SAML Integration Support</li>
<li>Full API to make user customization or custom integrations easier.</li>
</ol>
Please keep in mind that this program is in its early stages. As such, feature lists, and plans may change from time to time.
