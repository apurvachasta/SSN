<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <title>SSN ENTERPRISE</title>
        <link rel="stylesheet" href="./css/style.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" />
    
    </head>


    <body>
        <section class="header">
            <nav>
                <a href="index.html">
                    <h1>SSN ENTERPRISE</h1>
                </a>
                <div class="nav-list" id="navlist">
                    <i class="fa fa-times"  onclick="hideMenu()"></i>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="./HTML/about.html">About</a></li>
                        <li><a href="./HTML/products.html">Products</a></li>
                        <li><a href="./HTML/contactus.html">Contacts</a></li>
                    </ul>
                </div>
                <i class="fa fa-bars" id="bar"  onclick="showMenu()"></i>
            </nav>
        </section>

        <section class="home">
                <h1>Welcome to S.S.N Enterprises</h1>
                <p>Specialized Valve Manufacturer, Importer, Trader & Dealer different types of industrial Valves & Fittings.</p>
        </section>

        <section class="footer">
            <div class="links">
                    <h2>Useful links</h2>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="about.html">About</a></li>
                        <li><a href="products.html">Products</a></li>
                        <li><a href="contactus.html">Contacts</a></li>
                    </ul>
            </div>

            <div class="product-categories">
                <h2>Product Categories</h2>
                <div class="product-list">
                    <ul>
                        <li>Erasers, Pencils, Sharpners & Scales</li>
                        <li>Writing pads</li>
                        <li>Refills & Inks</li>
                        <li>Computer Paper,Rolls & Speciality</li>
                        <li>Spiral Pad</li>  
                    </ul> 
                    <ul>                     
                        <li>Mech. Pencils and Leads</li>
                        <li>Table Top Accessories</li>
                        <li>Writing & Display Boards</li>
                        <li>Stapler Pins & Punches</li>
                        <li>Notebooks</li>
                    </ul>
                    <ul>
                        <li>Display Books Liver Arch Files</li>
                        <li>Ring Binders & CD Zippers</li>
                        <li>Pin Dispensers & Trays</li>
                        <li>Ball Pens & Gel Pens</li>
                        <li>Markers & Highlighters</li>
                    </ul>
                </div>
            </div>

        </section>

        <script>
            var navlist = document.getElementById("navlist");

            function showMenu(){
                navlist.style.right = "0";
                navlist.style.transition="1s";
            }

            function hideMenu(){
                navlist.style.right = "-220px";
                navlist.style.transition="1s";
            } 

        </script>


    </body>
</html>