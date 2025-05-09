Automa Rules for Solo Play (App-Assisted Implementation)

Here's how to use your rules with the app:

Setup:

Manual: Choose Civilization/Capital City mats, place Landmark miniature on Era II income mat space, place resource cubes on the physical resource tracker (space '2').
App: The app starts Automa with 4 resources automatically. You can use the "Adjust Resources" button to change this if needed.
Manual: Give Automa territory tile and tapestry card, add the third player color, perform the initial Explore action for the third color (using Automa card for direction).
Automa Turns:

App: The app determines if Automa takes an Advance Turn or an Income Turn based on its internal logic (can it afford an advance based on its current resources and position?).
Action: Click the "Automa Turn" button in the app.
Advancement Turn:

App: The app calculates which track Automa advances on based on your selected Automa Character (Normal or Strategic) and the implemented priority rules. It automatically deducts the resource cost for the advance.
App: The app automatically moves Automa's token on the chosen track.
App: The app automatically claims track landmarks if Automa's token crosses or lands on them and they are available.
App: The app automatically updates Automa's building count if the space reached grants a specific building or a choice (it will take the first option listed in the app's data for that space).
Manual: You need to manually apply all other benefits and bonuses listed on the space Automa lands on in the physical game (e.g., gaining territory tiles, tapestry cards, VP, workers, performing Explore/Conquer actions, upgrading tech cards, etc.). The app does not simulate these effects beyond updating position, resources, buildings, and track landmarks.
Manual: The rule about paying for bonuses in Era III & IV is not automated by the app's resource cost calculation for advancement. You will need to manage this manually in the physical game if a space benefit requires spending resources for a bonus.
App Logic: Your "Favorite Track Priority" rules (Tier IV, Tied with player, 1 space before Landmark) are similar to the priority rules implemented in the app's Normal character logic (Rules 1, 2, 3). The app's Strategic character uses different priorities. The app uses a random permutation as a tiebreaker when multiple tracks meet the highest priority rule, replacing the need to use Automa cards for this specific tiebreaker.
Military Track Actions:

Manual: All aspects of the Conquer action (determining target based on proximity to center/outposts, rolling dice, gaining resources/benefits from dice, handling ties with Automa cards) are manual and not tracked by the app.
App: The app only tracks Automa's position on the Military track and claims Military track landmarks.
Building and Landmark Placement:

Manual: Placing buildings and landmarks in the Capital City is manual and not tracked by the app.
App: The app tracks the count of each building type Automa has and the status of all landmarks (available, player, automa, gone). You can use the "Landmark Status Control" section and the "Adjust Buildings" modal in the app to manually update these if needed (e.g., if Automa gains a landmark from a tech card or places a building in its city).
Technology Track Actions:

Manual: Choosing/gaining/placing/upgrading Tech cards, rolling dice for choices, and applying specific space effects (like discards, replacements, activating circle/square benefits) are manual and not tracked by the app.
App: The app only tracks Automa's position on the Technology track and claims Technology track landmarks.
Science Track Actions:

Manual: Rolling the Science die, advancing on the rolled track, and gaining/ignoring benefits/bonuses based on the research icon are manual and not tracked by the app.
Manual: Applying specific space effects (like advancing/regressing on other tracks) is manual and not tracked by the app.
App: The app only tracks Automa's position on the Science track and claims Science track landmarks.
Exploration Track Actions:

Manual: Managing Territory tiles, placing Outposts, gaining benefits from tiles, exploring space tiles, and applying specific space effects are manual and not tracked by the app.
App: The app only tracks Automa's position on the Exploration track and claims Exploration track landmarks.
Arts Track Actions:

Manual: Managing Inspiration tiles, gaining/choosing/broadcasting Masterpiece cards, rolling dice for choices, and applying specific space effects are manual and not tracked by the app.
App: The app only tracks Automa's position on the Arts track and claims Arts track landmarks.
Income Turn:

App: The app indicates when Automa takes an Income Turn and prompts you to input the results via a modal.
Manual: You must manually perform all the steps of the Income Turn in the physical game (Masterpiece benefits, Civilization ability, playing Tapestry card, upgrading Tech card, scoring Capital City).
App Input: Use the app's Income modal to manually input Automa's final resource count, the number of buildings gained during this income phase, and any landmarks gained during this income phase (e.g., from a Masterpiece or Civilization ability). Confirming the modal updates the app's state.
Combat:

Manual: Combat resolution is entirely manual and not tracked by the app.
Gaining a New Civilization:

Manual: Gaining new Civilizations and using the "Automa new civ board" are entirely manual and not tracked by the app.
General Automa Choices:

Manual: For any choices not directly related to track advancement (e.g., on cards, abilities), you should use dice rolls or other manual methods as described in your rules.
App Logic: The app handles the choice of which track to advance on based on its internal priority rules and tiebreaker logic.
In summary, the app automates tracking positions, resource costs for advances, track landmark claiming, building counts (when gained from track spaces or manually adjusted), and the core Automa Advance/Income decision based on affordability and character priorities/tiebreakers. Everything else in your detailed rules still needs to be managed manually in the physical game. The app serves as a digital tracker and decision-maker for the main advancement action.
