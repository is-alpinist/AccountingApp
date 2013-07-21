This is a production accounting application by jason richert

This is a multi-user purchase order draw down application.

The modle is:

Purchase order:
PO* <related>
Initial Amount 
Date
Description
Vendor Name

Drawdown:
Type [Invoice or Adjustment]
Invoice*
PO* <related> 
From Date
To Date
Description
Amount

All of this is behind USER login without signup

There is a printable report.
Would like to add the scanned copy of the PO later for prinitng with the report.

