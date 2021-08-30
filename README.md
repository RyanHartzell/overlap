# overlap
Mapping skillsets, interests, and program needs across closed groups in support of R&amp;D efforts

TODO:

Init angular project
Install npm dependencies for graph visualization and graphql + apollo + prisma + postgres or mongodb support (API and data persistence)
Build out basic index page
Build basic schema for user and auth, and "node" design (basic data 'describing' each User in the system)
Implement API and CRUD operations on database
Test API and database
Build visualizer for all nodes in network involving perceived connections on keywords (and later, sentiment/topics) + filtering and view support when inspecting
Build helper for choosing fields on each node in app by a non-SME admin depending on needs of team at different levels. Certain people should be able to search on whatever data is relevant to them, and everyone should be able to view results relative to the team's organization in real life.
Support for saving results or doing batch notifications based on results, i.e. triggering some arbitrary event (send an email to everyone who met some criterion, invite some group to a teams meeting, serialize results into JSON, etc) 
