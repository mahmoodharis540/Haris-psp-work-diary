# Tips for the Sprint Week
Monday 23rd march 

Deployment works 

Let everyone branch off it 

Held standup assigned tasks 

Reviewed the code everyone did and merged branches 


24th March 

Held standup 
Build the node modules pages 
Consulted on the BFS algorithm 
Helped fix some coding issues for sam
Change pathfinding to be able to select existing nodes and to reflect database changes.
Reviewed the code everyone did and merged branches 



25th March 
Held standup – suggested we tick off “Tick off User stories” I made in first sprint so we can see what user stories are completed and what needs to be done 

Reviewed the code everyone did and merged branches 

Checked the BFS algorithm works with the code I made, and Sams languages work merged with the work we did

Assigned new tasks: 
Felipe and Jack merging BFS branches
And me and start working on new user stories.

Prepped demonstration and notes for the next client meeting 


Thursday 26

Prune branches – everyones work is in
Find additional tasks 
•	Refactored the accessibility controls from a permanent floating dock into a popup opened from a single floating accessibility icon.
•	Made the popup auto-collapse after 5 seconds.
•	Changed the accessibility trigger icon to a standing person icon.
•	Made the accessibility popup responsive so it scales better across desktop and mobile.
•	Improved accessibility controls:
•	A+ and A- now update the same stored text-size setting used in Settings.
•	added a working screen-reader/read-aloud helper.
•	added dyslexia-friendly font mode.
•	added visible link highlighting.
•	added reduced-motion and high-contrast toggles.
•	Added a per-step read-aloud button on the directions page so the current instruction text can be spoken.
•	Moved the floating accessibility icon to be global so it appears on every page in the bottom-right.
•	Changed the screen reader from a one-off action into a persistent enabled/disabled mode that continues across page navigation until turned off.
•	Made the floating theme/settings/accessibility controls more mobile-friendly so they take less space on small screens.
•	Removed the slide counter from the directions page header and re-centered the route title.
full-path-url
•	Extended the homepage QR/prefill flow so a single URL can fill both:
•	Where are you:
•	Where is your appointment:
•	Added support for:
•	entranceId
•	destinationId
•	with name fallback where needed.
•	Added a new destination lookup API route:
•	/api/destinations/[id]
•	Made the destination field controlled so the second prefilled value actually appears in the UI.
•	Added new status messages for:
•	entrance only
•	destination only
•	both entrance and destination.
•	Added a new Patient Route QR section to the admin Graph Editor page.
•	That admin section can now:
•	generate a full patient route URL
•	generate a QR code for that URL
•	preview/download the QR code
•	create a prefilled patient email draft with the route link.
•	Fixed dev caching/service-worker issues that were causing stale localhost behavior and hydration mismatches.
•	Added directions-page translations for the read-step button and other directions UI labels.
•	Translated more of the directions page UI so app-owned text follows the selected language.
offline-routes
•	Added offline route support so previously loaded route data and media can continue working when Wi Fi drops.
•	Added a service worker and registration flow.
•	Cached:
•	route lookup data
•	path sequence data
•	uploaded route media.
•	Added an offline banner on the directions page.
•	Designed the flow so if a route is loaded once while online, it can still be followed after connectivity drops.
•	This branch focused on resilience for unreliable hospital Wi Fi rather than new routing logic.
•	added copy email, add recipient name and appointment time and so you can copy and paste email as an option

