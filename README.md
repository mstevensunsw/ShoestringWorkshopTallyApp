# Shoestring Workshop Tally App - User Guide

## Overview
The Workshop Tally App is a mobile-friendly tool for recording participant votes during Shoestring Digital Manufacturing needs identification workshops. It allows facilitators to quickly tally green (Priority) and yellow (Interesting) sticker votes across all solution areas and export results for analysis.

## Quick Start

### 1. Open the App
- Open `workshop_tally_app_v3.html` in your mobile browser (Chrome, Safari, Firefox, etc.)
- Works offline once loaded
- No installation required

### 2. Enter Workshop Details
- **Workshop Date**: Select the date using the date picker
- **Workshop Location**: Enter location (e.g., "Queanbeyan", "Bega Valley", "Central Coast")

### 3. Record Votes
- Select a category from the dropdown (PRICE, QUALITY, DELIVERY, etc.)
- For each solution area, tap the **+** buttons to increment vote counts:
  - **Green counter** = Priority votes (green stickers)
  - **Yellow counter** = Interesting votes (yellow stickers)
- Use the **−** buttons to correct mistakes
- Switch categories and repeat

### 4. Export Results
Two export options available:

**📊 Export Raw**
- Shows every solution area under every category
- Good for seeing which categories generated most interest
- Includes duplicates across categories

**📈 Export Aggregated** (RECOMMENDED)
- Combines duplicate solution areas across all categories
- Shows only 39 unique solution areas with total votes
- Sorted alphabetically
- Includes a TOTAL row
- Best for overall workshop analysis

### 5. Reset for Next Workshop
**Before starting a new workshop:**
- Tap **⚠️ Reset All Data** button
- Confirm twice (it's permanent!)
- Enter new workshop date and location
- Start tallying fresh

## Key Features

✅ **Auto-Save**: All data saves automatically to your browser  
✅ **Works Offline**: No internet needed during the workshop  
✅ **Mobile Optimized**: Large tap targets, easy to use with one hand  
✅ **Quick Tallying**: Fast increment/decrement buttons  
✅ **Category Summary**: Real-time totals for current category  
✅ **Smart Export**: Filenames include location and date  
✅ **Data Persistence**: Close the browser and data remains  

## Workshop Categories

The app includes all 10 workshop categories:
- PRICE
- QUALITY
- DELIVERY
- AGILITY
- SUSTAINABILITY
- PEOPLE & INFORMATION
- PLANT & EQUIPMENT
- SUPPLY CHAIN
- DEMAND MANAGEMENT
- CASH FLOW

## Solution Areas

**Total unique solution areas**: 39  
**Total instances across categories**: 153

Some solution areas appear in multiple categories (e.g., "Capacity monitoring" appears in 7 categories). The aggregated export automatically combines these for you.

## Best Practices

### During the Workshop
1. **One person tallies**: Designate one team member to use the app
2. **Tally immediately**: Record votes as posters are collected or photographed
3. **Double-check**: Use the category summary to verify totals
4. **Count systematically**: Work left-to-right, top-to-bottom on each poster

### Data Management
1. **Export immediately**: Export results right after the workshop
2. **Backup exports**: Email CSV files to yourself as backup
3. **Clear between workshops**: Always reset before a new workshop
4. **Name consistently**: Use consistent location names (e.g., always "Central Coast" not "CC")

### Tips
- If you accidentally close the browser, your data is safe—just reopen the app
- You can pause and resume tallying anytime
- The app works great on tablets too
- Take a photo of each poster as backup before tallying

## Troubleshooting

**Q: Can I use the app on multiple devices?**  
A: Each device stores its own data locally. Stick to one device per workshop.

**Q: What if I need to edit data after exporting?**  
A: Open the CSV file in Excel/Google Sheets and edit there, or correct values in the app and re-export.

**Q: Do I need internet during the workshop?**  
A: No! Once loaded, the app works completely offline.

**Q: Can I recover data after hitting "Reset All"?**  
A: No, it's permanent. Always export first!

## File Versions

- **V0**: Basic tally with raw export
- **V0.1**: Adds aggregated export option
- **V1** Adds workshop metadata and reset all functionality

## Export File Examples

### Raw Export
```
Workshop Date: 2024-11-27
Workshop Location: Queanbeyan

Category,Solution Area,Priority (Green),Interesting (Yellow)
"PRICE","Job tracking",5,3
"PRICE","Capacity monitoring",8,2
"DELIVERY","Job tracking",4,5
"DELIVERY","Capacity monitoring",6,1
...
```

### Aggregated Export
```
Workshop Date: 2024-11-27
Workshop Location: Queanbeyan

Solution Area,Total Priority (Green),Total Interesting (Yellow),Total Votes
"Capacity monitoring",14,3,17
"Job tracking",9,8,17
...
"TOTAL",145,87,232
```

## Support

For issues or questions, contact Michael Stevens.

---

**Version**: 3.0  
**Last Updated**: November 2024  
**Created for**: Shoestring Digital Manufacturing (University of Cambridge, UNSW Canberra and other Shoestring Partner Organisations)

