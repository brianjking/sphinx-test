Neova Event Processing Changelog & Release Notes
------------------------------------------------

**DD3-PR2.1 - 1 October 2015**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

New Features & Functionality in DD3-PR2.1 - 1 October 2015
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

-  Title Reduction Highest Title Mismatch squashed.
   [STRIKEOUT:*(DD3-937)*]

--------------

**DD3-PR2 - 29 September 2015**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

New Features & Functionality in DD3-PR2 - 29 September 2015
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

--------------

-  *Regular Finals* for Speed Retrieve & Extreme Vertical have now been
   fixed. [STRIKEOUT:*(DD3-807, DD3-396, DD3-810, DD3-808, DD3-679)*]
-  Last update to production (DD3-PR1.1) introduced an issue where some
   teams couldn't reset password from system generated password. This
   has been fixed. [STRIKEOUT:*(DD3-825)*]
-  *Special Finals* for Speed Retrieve & Extreme Vertical have now been
   hidden as we do not use them. [STRIKEOUT:*(DD3-396)*]
-  As an Onsite Admin/Office Admin you're now able to remove a team from
   a Wave using the "Delete" icon when in the "Groups" tab of any Big
   Air, Speed Retrieve, or Extreme Vertical Wave. *Please note that you
   cannot remove teams from Iron Dog Waves at this time. (DD4-78 &
   DD4-79) * ***It is VERY IMPORTANT to NOT USE THE "VIEW REGISTRATIONS"
   feature to delete any teams from Waves after an event begins as they
   will be deleted, however, the legs will remain towards a Title and WE
   DO NOT have a method of deleting them.***
-  To delete a Team from a Wave you must set their "STATUS" field to a
   "STATUS" of something other than "OK" or "--". *Acceptable values are
   "SCRATCH", "TIMEOUT", "DNQ", "DQ". You must select this status for
   BOTH J1 & J2 of the team you're looking to remove before clicking the
   Delete button in the corresponding row.*
-  Transactions Log now improved and shows in the appropriate accordion
   mode and doesn't have a broken UI when expanding for additional
   details. Simply click a row and it expands with the details. *Office
   Admin only* [STRIKEOUT:*(DD3-805)*]
-  **WAVES NO LONGER CLOSE 30 minutes before the Wave starts.** Onsite
   Admins & Office Admins can now ADD TEAMS throughout the entire course
   of the event to any Wave(s). [STRIKEOUT:*(DD3-172 EPIC)*]
-  "Active" Status Indicator on "EV Score Sheet" is now showing the
   correct designations. [STRIKEOUT:*(DD3-347)*]
-  Fixed an issue where if there are 0 teams in the First Wave the
   Bubble Sheet & Alternates for Big Air Finals would not generate
   [STRIKEOUT:*(DD3-698)*]
-  SSL Certificates for dockdogsevents.com & manager.dockdogsevents.com
   have been updated to continue to keep the application secure.
   [STRIKEOUT:*(DD3-783)*]
-  Fixes for dockdogs.com & dockdogsevents.com Rankings UI to
   standardize columns & PDF exports. [STRIKEOUT:*(DD3-9 & DD3-699)*]
-  Fixes for dockdogs.com Title Lists & PDF exports
   [STRIKEOUT:*(DD3-240)*]

Known Issues & Important Notes with DD3-PR2 - 29 September 2015
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

-  When deleting teams from Waves status field must be something other
   than "OK" or "--". *Acceptable values are "SCRATCH", "TIMEOUT",
   "DNQ", "DQ". You must select this status for BOTH J1 & J2 of the team
   you're looking to remove before clicking the Delete button in the
   corresponding row.*
-  Cannot use **"View Registrations"** to delete teams after scores have
   been assigned or we'll end up with extra legs assigned. **VERY
   IMPORTANT**.
-  Some issues with rankings are being resolved and will be posted as a
   patch ASAP.
-  You cannot delete a team from an Iron Dog Wave at this time. *(DD4-78
   & DD4-79)*
-  **It is VERY IMPORTANT that you fill in the boxes with details as to
   why you're discounting using a coupon or issuing a complimentary
   Wave.**
-  Title Reduction Highest Title Mismatch (DD3-937)
-  Titles PDF Export on dockdogs.com is creating corrupt PDFs despite
   working on staging environment, expect to be patched shortly.
   [STRIKEOUT:*(DD3-935)*]

**DD3-PR1.1 - 15 September 2015**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

New Features & Functionality in DD3-PR1.1 - 15 September 2015
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

-  Manually overriding standings in Big Air, Speed Retrieve, Extreme
   Vertical or Iron Dog Finals no longer causes the user interace to
   break. [STRIKEOUT:*(DD3-811)*]

Known Issues with DD3-PR1 - 11 September 2015
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

-  If attempting to add a new team as an onsite administrator and a
   Handler with the same FIRST NAME, LAST NAME, & EMAIL ADDRESS exist
   you'll be shown an error messsage stating to enter their username and
   use the "Already a Handler" button. *(DD3X-3)*
-  Printed receipts may show incorrect price for Youth Handlers on them.
   *(DD4-50)*
-  *"Regular Finals"* & *"Special Finals"* types for Speed Retrieve &
   Extreme Vertical are not working properly. *(DD3-807, DD3-396,
   DD3-810, DD3-808, DD3-679)*

**DD3-PR1 - 11 September 2015**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

New Features & Functionality in DD3-PR1 - 11 September 2015
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

--------------

-  You can now enter scores for Big Air, Speed Retrieve, & Extreme
   Vertical by typing into the boxes. *(How fast is it now?)*
-  You can now use the TAB KEY on the keyboard to tab between J1 & J2
   fields for Big Air, Speed Retrieve, & Extreme Vertical. After
   entering J2 clicking tab again will take you to the next row.
-  The **STATUS** field now defaults to **OK** in all disciplines.
   ***When using the TAB key to navigate between score entry fields you
   will need to click TWICE when going from J1 to J2 as the 1st click of
   TAB from the J1 box will activate the dropdown for the status field,
   clicking the 2nd time will move the cursor to J2.***
-  When processing BA, SR, & EV Finals you will no longer be tormented
   by the neverending sound of your mouse as you click "Add Alternates"
   one by one until the end of time. You can now select multiple
   alternates all in one swift click of the "Add Alternates" button.
   **Be sure to generate/re-regenrate the Bubble Sheet before attempting
   to process finalists. *Be sure to click on the Waves tab of each wave
   to record legs towards titles while processing events.***
-  Since you're not magic and people are not born in the future onsite
   admins, office admins, and Handlers are all prohibited from entering
   a DOB that is in the future. The same is true of a dog's DOB.
-  The dreaded "Add New Team" error messages lacking any feedback as to
   what's wrong are banished, we've kicked them off the island never to
   return.
-  You can now add Handlers & Dogs with apostrophes in their names.
-  Editing Handlers & Teams as an office admin is now fixed for those
   Handlers & Teams that we couldn't previously fix.
-  Handlers that couldn't edit their own accounts/teams can now do so
   without issue.
-  Newly created teams for all user types default to ***LAP DOG ==
   NO.*** *(Just because your dog sits on your lap doesn't make your
   Great Dane a Lap Dog.)*
-  Financial Transactions Log has the enhancements included. *(Office
   Admin only)*
-  BA, SR, EV, & Regular ID PDFs now print on legal size paper in
   landscape orientation. ***PLEASE DO NOT PRINT THESE REPORTS AS YOU
   SHOULD CONTINUE USING EXCEL AND/OR A5 UNTIL FURTHER NOTICE AS YOUR
   PRIMARY EVENT PROCESSING RESOURCE.***
-  Various typos have been corrected throughout the admin & handler
   areas.
-  Event Registration flow shows Team Name & Dog Name, no more confusion
   if a handler has multiple dogs which participate under the same *Team
   Name*.
-  Columns are displaying the correct details and are finally *nearly*
   usable throughout the manager.dockdogsevents.com application.
-  PDF/Printed reports no longer have overlapping text, are all
   formatted landscape, use legal size paper, etc.

Known Issues with DD3-PR1 - 11 September 2015
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

-  Manually overriding standings in Big Air Finals causes the user
   interface to break *(DD3-811)*
-  If attempting to add a new team as an onsite administrator and a
   Handler with the same FIRST NAME, LAST NAME, & EMAIL ADDRESS exist
   you'll be shown an error messsage stating to enter their username and
   use the "Already a Handler" button. *(DD3X-3)*
-  Printed receipts may show incorrect price for Youth Handlers on them.
   *(DD4-50)*
