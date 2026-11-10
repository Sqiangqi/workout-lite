# Workout Lite version history

Newest first. The version number matches the full claude.ai app version at the time of each update; web-only updates in between add a sub-version (e.g. 0.2d.1). Generated from `APP_VERSIONS` in `index.html`.

## 0.2f · 11/10/2026

Matches the full app Ver 0.2f. Pull Up: the card shows your body weight (the weight you typed on the Food tab or on the card; Edit to change it) and a Band switch with the band help in lbs; with no body weight the card asks for it and the reps are greyed out. Each set is saved as its own row: Weight = band help (0 = no band), Reps = that set. Progress charts the weight you pulled (body weight − band) with a dashed line at your body weight; body weight itself is never written to the workout Sheet. Time exercises (Warm-up, Battle Ropes): a countdown timer on the card (− / + to set it, Start / Pause / Reset, beeps at 0:00 and enters the time; Pause enters the time done so far); typing the time still works. Week plan: choose the plan length (2-10 days) on a number wheel; day 1 is a Monday and the plan repeats after the last day; the days show as circles (M T W R F S U) with a gold check once saved. Tapping a day opens a page like the Library (search, body-part keywords, body figure) where you tap exercises to add them; the picked ones sit on top in small type, swipe one left to remove it (Undo in the message). No day-type buttons any more: the day is named from what you pick (Upper body, Lower body or Combined; Upper gets a push or pull tag when more than half are push or pull; nothing picked = Rest day). Library: exercises are small tags around a body figure (back by the head, shoulders, chest, arms, core at the waist, legs at the bottom); the search box (name or muscle) and keyword chips light up the matching tags and grey out the rest; tap a tag for its picture, last session and ☆. Pinch with two fingers to zoom an enlarged exercise picture (double-tap to reset).

## 0.2e · 11/09/2026

Matches the full app Ver 0.2e. Swipe to remove: swipe an exercise card on Today, or a row on the Food tab (Eaten list, Adding list, Quick add › Edit list), all the way left; a red Remove shape grows out of the right edge, and letting go past about 40% of the width removes it. This replaces the × buttons and the Remove? confirmation on Today cards; a very thin red line on the right edge shows what can be swiped away. Undo in the message, except for a saved Eaten row (that one is deleted from your food Sheet). Swiping needs a touch screen. Food: tapping a Quick add food adds it to the Adding list right away at its usual amount (the amount box and Add button are gone; change the amount in the Adding list). Target / Left numbers are now bars for calories, carbs, protein, fat and fiber: eaten is solid, the Adding list is lighter, the number on the right is what is left, over target turns the bar red with +amount, and fiber shows a check when met. Messages now show small at the very top of the screen instead of over the middle. (Photo Replace / Delete from the full app is not included: the web version has no Photos tab.)

## 0.2d.1 · 11/08/2026

Web-only fixes on Ver 0.2d. The "Tap again to ..." confirm buttons (Sign out / switch account, Reset day, Use a different Sheet, Use a different food Sheet, Delete plan) showed red text on a red button, so the second tap prompt could not be read; they are now deep red with bold white text in light and dark mode. The Progress tab opens even when no exercise is starred or in a week plan, with a note on how to get a chart, instead of staying on the previous tab.

## 0.2d · 11/08/2026

Matches the full app Ver 0.2d. Settings is one grouped list like iPhone Settings: a row per section with an icon; tap a row to open it right under the row (which ones are open is remembered on this phone). Appearance: Follow the phone setting is a switch under Dark mode (Dark mode greyed out while it is on); Color theme (Navy + Gold, Soft ember, Blush; changes every navy and gold, light and dark); App icon: tap the logo at the top left to upload your own picture (cropped square from the middle) or go back to the default logo; it is saved in your Workout Lite folder in Google Drive, so it shows on every phone. New Settings › Carb week (your weight, then high / mid / low carb per weekday; the same as the Food tab). The Start each day with the plan switch moved into the Week plan card; the Week plan row shows the name of the plan in use. Exercises tab: favourite cards fold to their name (tap to open; Expand all / Collapse all). The header says No plan today when no week plan is in use.

## 0.2c · 11/08/2026

Matches the full app Ver 0.2c. Plan numbers are gone from exercise names (hidden too if your Sheet still has them); with no week plan in use Today starts empty. Exercises tab and Add an exercise: Favourites first, then the rest A to Z. New people get Dead Hang (stopwatch: Start, then Stop records the seconds; a small box for a typed time) and Pull Up (count only, + set for more; the Progress chart adds up each day; start and end drawing); anyone can add such exercises with the new reps unit or the seconds unit. Bottom sheets keep their last option above the iPhone home bar and away from the rounded corners. The Remove? confirmation on a Today card is a full-size red button. Progress: Show body weight on the chart is for the owner only.

## 0.2b · 11/07/2026

Matches the full app Ver 0.2b. Food tab: changing the Carb day is for that day only; Carb day › Plan my week sets the weekly high / mid / low pattern (one switch per weekday, with Standard 2-3-2, Match my workouts and All mid). The Weight box no longer shows Auto (7-day Renpho average) to anyone but the owner; everyone else types their weight. Week plan, one-day changes, typed weight, body type and unit are kept in a Food settings tab of the food Sheet, so they follow you to a new phone. Everything on the Food tab shows before a weight is set; the Weight box glows gold until then.

## 0.2a · 11/07/2026

Matches the full app Ver 0.2a. New person: the first-open screen makes a folder named Workout Lite in your My Drive with two Google Sheets, Workout Lite log (exercises, sessions, week plans) and Workout Lite food (food log, quick foods, body weight), in one tap. If the folder is already there it is reused and finished. Creating a food Sheet later also puts it in that folder. Sign-in now asks only for your email and for the files the app made itself, so Google shows no "unverified app" warning; the app settings and unsaved sets are kept in the Workout Lite folder. Using a Sheet the app did not make (Use a Sheet I already have) asks once for the full Google Sheets permission. Settings › Google account: Sign out / switch account (clears your data from this phone; the next sign-in lets you pick the account). Food tab: everything shows from the start; until a weight is set, the Weight box glows gold and a card with Enter my weight takes the place of the targets.

## 0.2 · 11/07/2026

Matches the full app Ver 0.2 (its 0.1v to 0.2; this update was first listed here as 0.1h). Food tab: one row with Weight (Auto = average of your Body metrics days in the past 7 days, or Manual; kg or lbs; the typed weight is kept on this phone), Body type (Ectomorph 3 g/kg carbs, Mesomorph 2.5, Endomorph 2; Mesomorph is the default) and Carb day, each opening a list at the bottom; Manual adjustment under Suggested (add or take away grams of carbs, protein, fat or fiber, saved as their own rows); legend for the week dots. The + bubble is replaced by Add food › Enter myself.

## 0.1g · 11/06/2026

Web version (GitHub): Food tab from the full app Ver 0.1u, without Claude calorie estimates: carb-cycling targets from your weight, Quick add, suggestions (3), Add a food (+ bubble), fiber, week bar with arrows. Food is kept in your own food Sheet (create one, or use one you have); type your weight if the Sheet has no Renpho readings. Also from the full app: the top weight and its reps as the hint in every set box. The Apps Script version is unchanged.

## 0.1f · 11/03/2026

From the full app Ver 0.1m: Settings › Week plan (up to 3 named plans kept in a Plan tab of your Sheet; day types Upper, Push, Pull, Lower, Custom, Rest; pick and drag exercises; saved day by day), Today shows the current plan and switches plans, ★ favourites per person, exercise notes shown only to the owner, no Notes field when adding an exercise. LAST UPDATE of Workout Lite: it will not be updated after this version; new features go to the full app only.

## 0.1e · 11/01/2026

Sets with only a weight (no reps) are saved too. Settings > Today's plan: switch off to start each day empty and pick exercises yourself (kept per phone). From the full app Ver 0.1j.

## 0.1d · 11/01/2026

One update for both: the Apps Script version now loads this page from GitHub (sqiangqi.github.io/workout-lite/lite.html) each time it opens, falling back to its built-in copy; the GitHub web version gets the same page. Settings > Version shows where the page came from.

## 0.1c · 11/01/2026

Library: Add an exercise is now a round gold bubble at the bottom right with a circling halo; it opens a low bottom sheet with tap buttons for category, unit and plan days (same as the full app Ver 0.1i).

## 0.1b · 11/01/2026

Library: Add an exercise to the list (name, category, unit, plan number, muscle, notes), same as the full app. Units come from the Unit column (F) of the Exercises tab. The link to the full version was removed (iOS cannot open the Home Screen app from a link).

## 0.1a · 11/01/2026

Bigger tab labels (four tabs now). Owner only: tap the logo or Settings > Full version to open the full claude.ai app (removed in 0.1b).

## 0.1 · 11/01/2026

First version of Workout Lite: runs on Google Apps Script without Claude. Today, Progress, Library and Settings from QS Workout Ver 0.1g; each person signs in with Google and saves to their own Sheet.
