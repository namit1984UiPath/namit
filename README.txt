A demo project is available here.



sapbapi\ folder has some BAPI generated using the SAP Connector Wizard.

data\ folder has input data to these BAPIs.

output\ folder has data that is saved by the GET BAPIs.

The demo is pre-configured with the S4H_FIN user connecting to the above system.


There are 2 XAMLs in the project folder to run sample scenarios.



Demo_BAPI_PO_CREATE.xaml

	This BAPI will create a Purchase Order and display the purchase order number.



	The data for this BAPI is in the data\ folder.
	Login to SAP GUI and use transaction ME22 to lookup the BAPI (using the Document Number shown in your message box).


Demo_GET_BAPIS.xaml

	This XAML will invoke 2 Read/Get SAP BAPIs.

	BAPI_USER_GETLIST will read the User List.

	BAPI_REQUISITION_GETDETAIL will read the Requisition.

	All data read will be saved in the output\ folder and message box will be displayed.
	The write happens between the two message boxes.
