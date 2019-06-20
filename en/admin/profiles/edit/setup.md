The Setup tab is used to set some standard properties for the profile, such as Name, Description, Enabled state and Ordering, as well as the Assignment - where and by who the profile is assigned to.

**Details**
-----------

**Name**

Set the name for the profile. This is used to identify the profile in the Profiles list.

**Description**

Set a description for the profile. This can be used to explain the profiles purpose.

**Enabled**

Set the profile state : **Yes** - the profile is enabled and will be used. **No** - The profile is not enabled and will not be used.

**Ordering**

This sets the order the profile will be loaded. Profiles are loaded from top (Order First) to bottom (Order Last). The first profile loaded that meets the assignment options will be used.

**Assignment**
--------------

The profile can be assigned to load on a particular device, in a Joomla area or component, and for a Joomla User Group or User. A combination of options can selected to create complex assignments.

**Area**

Select the Joomla area - Front-end and/or Back-end (Administration) - where the profile will be used.

**Device**

Select the device type the profile will be used on, eg: Phone, Tablet or Desktop.

**Components**

Select the Joomla Components the profile will be used in. By default all components are selected.

To select a specific component, click on the **Select From List** option, then select the required components from the list.

**User Group**

Select the Joomla User Groups to assign the profile to. At least one User Group or User must be selected for each profile.

**User**

Click the Add User button to assign a user to the profile. It is only necessary to assign a user to a profile if you have not assigned a User Group, or if the assigned user is not in any of the assigned User Groups.

**Example Profiles**
--------------------

**Front-end**

A profile for authors, editors and publishers only. This profile might include limited editing options.

- **Area** - Front-end
- **Components** - All Components
- **Usertypes** - Author, Editor, Publisher
- **Users** - Empty

**Admin only**

A profile for Administrators and Super Administrators

- **Area** - Front-end and Back-end
- **Components** - All Components
- **Usertypes** - Administrator, Super Administrator
- **Users** - Empty

**Newsletter**

A profile for a specific component such as a newletter component

- **Area** - Front-end and Back-end
- **Components** - Newsletter (if installed, select the newsletter components name)
- **Usertypes** - Publisher, Administrator, Super Administrator
- **Users** - joseschmo - This user is actually of usertype Editor but is allowed access to this profile.