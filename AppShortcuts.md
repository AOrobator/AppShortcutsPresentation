# Implementing App Shortcuts
## @AOrobator

--- 

# What are App Shortcuts? 

![right fit](https://github.com/AOrobator/AppShortcutsPresentation/blob/master/img/google_maps_shortcuts.png?raw=true)

* Introduced in Android 7.1 (API 25)
* Access to primary functions of your app
* Activated by long press on app icon
* Can be pinned to the home screen

^ Explain picture
^ Amex possible shortcuts -> Messaging, View Balance

--- 
# Types of Shortcuts

* Static
  * Defined in XML
  * Can only be updated with app updates
* Dynamic
  * Can be updated at runtime

---

# Live Demo!

^ Add metadata tag to manifest
^ Create shortcuts.xml
^ Run code to display static shortcut
^ Create ShortcutHelper.kt
^ Create ShortcutAction 
^ Define getConstellationVisitedCount()
^ Define updateShortcuts()
^ Call in onCreate() of application
^ Run code (show dynamic shortcuts, not dynamic yet cuz no trackin)
^ Define trackShortcutused()
^ Call it in ConstellationDetailActivity
^ Run App, go to constellation several times to make it appear in shortcuts list
^ Implement onOptionsItemSelected in ConstellationDetailActivity
^ Run app, pin shortcut, disable it

---

# Best Practices

* Follow design guidelines: [LINK](https://commondatastorage.googleapis.com/androiddevelopers/shareables/design/app-shortcuts-design-guidelines.pdf)
* Publish a maximum of four shortcuts
* Maintain shortcut and action usage history
* Dynamic shortcuts aren't preserved during backup and restore

---

# Questions?