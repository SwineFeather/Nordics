# Create BlueMap Markers

## **How to Create and Submit BlueMap Markers:**

BlueMap markers allow players to submit specific points of interest (POIs) on the map. These markers help others find key locations and add lore or history to the map. Here's how to submit a marker, including the formatting and what information is required.

### **1. Guidelines for Creating Markers:**

You’ll need to provide the following information to create a BlueMap marker:

* **Marker Name**: What will this marker be called? (E.g., Atlantis-Ruins)
* **Type**: The type of marker (usually `poi` for points of interest).
* **Position (x, y, z)**: The coordinates where the marker should be placed.
* **Label**: The name that will appear on the map for the marker.
* **Details**: Additional text explaining the significance of the location.
* **Icon**: Choose from a list of available icons (see below).
* **Anchor**: Define how the marker should be anchored visually, with X and Y axis positioning.
* **Sorting**: Optional. Sorting value for marker order.
* **Visibility**: Should the marker be listed and visible on the map? (Usually set to `true`).

### **2. Special Rules for Town Icons (Using Towny Plugin):**

Certain icons are restricted based on the size of the town in Towny. Follow these guidelines:

* **Village Icon**: For towns with **less than 4 players**.
* **Town Icon**: For towns with **5-14 players**.
* **City Icon**: For towns with **15+ players**.
* **Capital Icon**: For towns that are **capitals of nations**.
* **Ruins Icon**: Only used for **towns that have gone bankrupt**.

### **3. Available Icons:**

You can use the following pre-approved icons for your markers:

* **bank**, **battles**, **bridges**, **entertainment**, **hillMonsters**, **hotSprings**, **inns**, **libraries**, **lighthouses**, **mines**, **pirates**, **portals**, **rifts**, **ruins**, **sacredForests**, **sacredPalmGroves**, **sacredPineries**, **seaMonsters**, **statue**, **volcanoes**, **waterfalls**.

If your marker does not fall under any of these categories, you can request to create a new marker or use our **Photoshop file** to design one and submit it for approval.

### **4. Approval Process:**

Your marker must be reviewed and approved by a moderator. Not all markers will be accepted, but you can increase the chances of approval by submitting a complete form. If you want to suggest a new marker or location, you can also do so via our **Trello card** for markers.

**Marker Submission Form:**

Fill in the form below with the required details to submit your marker.

| **Field**              | **Your Input**                          |
| ---------------------- | --------------------------------------- |
| **Marker Name**        |                                         |
| **Type**               | `poi`                                   |
| **Position (x, y, z)** |                                         |
| **Label**              |                                         |
| **Detail**             |                                         |
| **Icon**               | Select from available icons (see above) |
| **Anchor (x, y)**      | `10, 15`                                |
| **Sorting**            |                                         |
| **Listed**             | `true`                                  |

**Example:**

```yaml
Atlantis-Ruins: {
    type: "poi",
    position: { x: -1662, y: 120, z: 5509 },
    label: "Atlantis Ruins",
    detail: "The legendary Atlantis, founded by MigningSM, is now submerged once more. Created on 2023-09-21 15:52:58.",
    icon: "assets/ruins.png",
    anchor: { x: 10, y: 15 },
    sorting: 0,
    listed: true,
    min-distance: 700,
    max-distance: 50000
}
```

### **5. Submitting a Marker Request (Trello Card)**

If you prefer not to fill out the form, you can request a marker by adding a Trello card. In the Trello card:

* **Marker Name**: Specify the name.
* **Type**: Describe the type of marker.
* **Details**: Provide as much context as possible.
* **Icon**: Select or describe the icon you want.

Include this information in the card, and the mod team will review it. Note that filling out the form will lead to quicker approval.

### **6. Photoshop File for Custom Icons:**

If you wish to create a custom icon, you can download our **Photoshop file** and follow the instructions to design your own icon. Once completed, upload the file and request approval through Trello or the form.
