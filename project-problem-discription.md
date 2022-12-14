# Project problem discription

Consider the situation of someone who needs to monitor their blood pressure and heart rate data. Make a simple, attractive, intuitive, Android mobile app to track this data. Let us call this app: CardiacRecorder.

Specifically, each measurement has the following fields:

• date measured (presented in dd-mm-yyyy format)

• time measured (presented in hh:mm format)

• systolic pressure in mm Hg (non-negative integer)

• diastolic pressure in mm Hg (non-negative integer)

• heart rate in beats per minute (non-negative integer)

• comment (textual, up to 20 characters)

Only the comment field may be left blank for a measurement.

The app should allow the user to:

• show a list of measurements

• add a new measurement (which always appends to the bottom end of the list)

• view and edit the details of an existing measurement

• delete a measurement

• see unusual blood pressures highlighted or flagged.

Normal pressures are systolic between 90 and 140 and diastolic between 60 and 90.

The list need not show all the information for a measurement if space is limited. Minimally, each record in the list should show the date, systolic pressure, diastolic pressure, and heart rate.

The app must assist the user in proper data entry. For example, use appropriate user interface controls to enforce particular data types and avoid illegal values.

The app must be persistent. That is, exiting and fully stopping the app should not lose data. Therefore, you need to store the data offline or online.
