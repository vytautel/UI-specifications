* __Initial view__
    * Top menu
    * Full width "users list"
    * "New user form" is hidden
* __Top menu__
    * "New user" button
        * On click, new user form appears. 
    * "Hide disabled user" checkbox
        * On click, users that has status “disabled” should not be shown    
    * "Save user" button (inactive)
* __Users list__. All users details table.
    * ID, user name, email and status (enabled, disabled) columns
    * Filters on each column
    * When table is filled, pagination appears to allow seeing next data portion. ~15 rows in one page. 
* __"New user" form__. Form to fill in new user details.
    * Username, display name, phone, email input fields. 
    * Enabled/disabled checkbox
    * User roles select input consisting of 3 values: Guest, Admin, SuperAdmin
    * When all information is filled, save user button becomes active
* __"Save user"__ button.
    * Inactive until new user form is filled. 
    * On click, data from "new user" form is send to server side and new user is added to users list. 

