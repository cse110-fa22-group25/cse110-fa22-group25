# ****Sleep Deprivation - Team #25****

# Wednesday Regular Meeting

## In person ****- Nov 2, 6:00pm - 7:20pm****

## Attendance

- Anish
- Ben
- Janav
- Karthik
- Rena
- Sia
- Siya
- Yiren
- Yong
- Xinyi

## Agenda

- Future assignments/due
- Cutting down some features for now
- How to assign tasks to each member

## Discussion

- Canvas Assignments regarding CI/CD pipeline
    - Last 3 assignments have already been done by Ben
    - Linting and code style
        - find a guideline and everyone should follow that
- localStorage
- Cutting down the features
    - Calendar view → just list view
    - User just put the malfunction history in profile page (notes section)
    - Maintenance Page/Main Page: a list view of maintenance dates
        1. bare minimum → display as they are entered, rather than by date
    - Maintenance Page: read/update/create/delete maintenance events with frequencies
        1. bare minimum → frequencies would not be applied directly to the dates
    - Searching/Filter:
        - the code for searching for a label should be similar to selecting a label
        - do category filter first
    - lower the priority for the content recommendation
- For the first version, only do the following parts:
    1. Main page: add a new product, view existing products
    2. Product Page: create/read profiles with the required information
    3. Product Page: delete product profiles
    4. Product Page/Malfunction page: update profiles with optional information
        1. information not required when first creating the profile
    5. Product Page/Malfunction page: read/add/update notes to the product profiles
        1. fault records — past breakdowns, how things were fixed, etc
    6. Main Page: filtering products by custom filters
        1. bare minimum → implement one-label selection
        2. no searching for the label → just filtering
        3. start with pre-set filters
- How to assign the tasks
    - by features/components
- (JS Object) Product:

```jsx
Object Product {
	title:
	serialNumber:
	tag:
	expDate:
	notes:
}
```

- Task assignments:
    - Product Add Page:
        - Xinyi, Siya, Ben Xia
    - Existing Product Page
        - Anish, Janav, Rena
    - Filters/Filtering
        - Yong, Ben, Janav

## Next Meeting

- Report difficulties