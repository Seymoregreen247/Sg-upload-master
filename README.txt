SG Ultimate POS — light theme + Admin

Open index.html in a browser or deploy the sg-ultimate-pos folder to a static host.
Use Admin to add products and set sale price, cost and stock. Existing products can be edited or deleted there. Inventory still supports quick additions and stock adjustments.

Data is stored in this browser's localStorage. It does not sync across devices or survive clearing browser data. Export or server sync is needed before relying on it for business records.
Cash App, Venmo and PayPal buttons only record a selected payment method; they do not charge a customer or verify payment. Confirm payment in the respective app before recording it here.

CSV upload: In Admin, download SG-Product-CSV-Template.csv. Required columns in this order: name,category,sku,quantity,price,cost. Name and price are required; quantity and cost default to zero. Use a unique SKU to update an existing product on later imports. A matching SKU replaces its catalog fields including stock; blank SKU creates a new product. A quoted CSV field may contain commas or line breaks. Invalid rows stop the entire import without changing catalog data.
