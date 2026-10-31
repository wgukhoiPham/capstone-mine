# capstone-mine# Vacation App

## Purpose
Vacation App is an Android application that helps a traveler plan trips. The user can save vacations (title, hotel, start date, end date) and the excursions that belong to each vacation (title, date). Data is saved on the device with the Room framework over a local SQLite database. The user can set alerts, and can share a vacation or an excursion.

## Directions for Using the App
Every item below matches a rubric requirement (B1 to B5).

**Home screen**
1. Open the app. The home screen says "Press Open to launch". Tap the **Open** button to go to the Vacation List.

**Add a vacation (B1, B2, B3a, B3b)**
1. On the Vacation List screen, tap the **+** button.
2. Enter a title and a hotel or lodging.
3. Tap the Start Date and End Date boxes and pick dates from the calendar.
4. Open the menu (three dots) and tap **Save Vacation**.

**Edit a vacation (B3b)**
1. Tap a vacation in the list to open its details.
2. Change any field, then open the menu and tap **Save Vacation**.

**Date validation (B3c, B3d)**
1. Save a vacation with an empty date. A message asks you to pick both dates.
2. Pick an end date before the start date and save. A message says the end date must be after the start date.

**Delete a vacation (B1, B3b)**
1. Open a vacation that has excursions, open the menu, and tap **Delete Vacation**. A message says it cannot be deleted while excursions exist.
2. Delete the excursions first, then delete the vacation. It is removed.

**Vacation alert (B3e)**
1. Open a saved vacation with valid dates.
2. Open the menu and tap **Set Alert**. Alerts are scheduled for the start and end dates.
3. On those dates a notification shows the vacation title and whether it is starting or ending.

**Share a vacation (B3f)**
1. Open a vacation, open the menu, and tap **Share Vacation**.
2. Choose an app (email, messages, or clipboard). The title, hotel, start date, and end date are filled in automatically.

**Add an excursion (B3g, B3h, B4, B5)**
1. Open a saved vacation and tap the **+** button.
2. Enter a title and tap the Date box to pick a date.
3. Choose the vacation in the dropdown.
4. Open the menu and tap **Save Excursion**.
5. The excursion appears in that vacation's excursion list.

**Excursion date validation (B5c, B5e)**
1. Save an excursion with an empty or invalid date. A message asks for a valid date.
2. Pick a date outside the vacation's start and end dates. A message shows the allowed range.

**Edit and delete an excursion (B3h, B5b)**
1. Tap an excursion in the list to open it.
2. Change the title or date and tap **Save Excursion**, or tap **Delete Excursion**.

**Excursion alert and sharing (B5d)**
1. Open a saved excursion, open the menu, and tap **Set Alert**. On the excursion date a notification shows the excursion title.
2. Tap **Share Excursion** to share its title and date.

## Android Version
- minSdk: Android 8.0 (API 26)
- The signed APK was built and tested: Pixel 6 Pro API 34/ Android 14.0 ("UpsideDownCake) | x86_64

## Git Repository

