#### JTableFiller
A simple library to fill your JTables fast.

Sample usage,
-  Add library
-  Add a JTable to your frame
-  Call `fillTable([ResultSet],[JTable model],[Column names],[Column indices]);` method

	`ResultSet rs = ...;`
    `JTableFiller filler = new JTableFiller();`
    `filler.filTable(rs,[JTable.getModel],null, null);`
    
    ![Imgur](http://i.imgur.com/nOCqbvN.png)
    
    fill with custom column names
    
    `ResultSet rs = ...;`
    `JTableFiller filler = new JTableFiller();`
    ` String[] names = {"Window ID","Title","Label"};`
    `filler.filTable(rs,[JTable.getModel],names, null);`
    
    ![Image](http://i.imgur.com/Ta3nOiR.png)
    
    fill with custom column index
    
    `ResultSet rs = ...;`
    `JTableFiller filler = new JTableFiller();`
    `int[] indices = {0,1};`
    `filler.filTable(rs,[JTable.getModel],null, indices);`
    
    ![Imgur](http://i.imgur.com/hWPchww.png)
    
    fill with custom column names and indices
    
    `ResultSet rs = ...;`
    `JTableFiller filler = new JTableFiller();`
    ` String[] names = {"Window ID","Title"};`
    `int[] indices = {0,1};`
    `filler.filTable(rs,[JTable.getModel],names, indices);`
    
    ![Imgur](http://i.imgur.com/CXrFHCP.png)
    
    Thats it.
    
Download `JTableFiller.jar`
    