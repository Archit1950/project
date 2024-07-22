<!DOCTYPE html>
<!-- saved from url=(0039)http://127.0.0.1:5500/project.html#menu -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Café Bliss</title>
    <link rel="stylesheet" href="./Café Bliss_files/styles.css">
    <style>
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fdf5e6;
        }
        
        .container {
            width: 80%;
            margin: 0 auto;
        }
        
        header {
            background-color: #6b4f4f;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        
        nav ul {
            list-style: none;
            padding: 0;
        }
        
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        
        .hero {
            background: url('https://images.unsplash.com/photo-1509042239860-f550ce710b93') no-repeat center center/cover;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 4px #000;
        }
        
        .hero h2 {
            font-size: 3em;
            margin: 0;
        }
        
        .hero p {
            font-size: 1.5em;
        }
        
        section {
            padding: 50px 0;
        }
        
        h2 {
            text-align: center;
            margin-bottom: 30px;
            font-size: 2.5em;
            color: #6b4f4f;
        }
        
        .menu-items {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        
        .menu-item {
            background-color: #fff;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 250px;
            text-align: center;
            position: relative;
        }
        
        .menu-item img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 10px 10px 0 0;
        }
        
        .menu-item h3 {
            margin: 10px 0;
            color: #6b4f4f;
        }
        
        .menu-item p {
            font-size: 1.2em;
        }
        
        .menu-item button {
            background-color: #6b4f4f;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }
        
        #order-summary {
            text-align: center;
            margin-top: 30px;
            font-size: 1.2em;
        }

        footer {
            background-color: #6b4f4f;
            color: white;
            text-align: center;
            padding: 20px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Welcome to Café Bliss</h1>
            <nav>
                <ul>
                    <li><a href="http://127.0.0.1:5500/project.html#home">Home</a></li>
                    <li><a href="http://127.0.0.1:5500/project.html#menu">Menu</a></li>
                    <li><a href="http://127.0.0.1:5500/project.html#about">About Us</a></li>
                    <li><a href="http://127.0.0.1:5500/project.html#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <section id="home">
        <div class="hero">
            <h2>Experience the Best Coffee in Town</h2>
            <p>Delicious coffee and cozy ambiance.</p>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Café Bliss is a cozy place to relax and enjoy a cup of coffee. We offer a variety of beverages and snacks. Our café is the perfect spot for meeting friends, reading a book, or getting some work done.</p>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact</h2>
            <p>Email: info@cafebliss.com</p>
            <p>Phone: +91-1234567890</p>
        </div>
    </section>

    <section id="menu">
        <div class="container">
            <h2>Menu</h2>
            <div class="menu-items">
                <div class="menu-item">
                    <img src="./Café Bliss_files/photo-1489866492941-15d60bdaa7e0" alt="Espresso">
                    <h3>Espresso</h3>
                    <p>₹150</p>
                    <button onclick="addToOrder(&#39;Espresso&#39;, 150)">Order</button>
                </div>
                <div class="menu-item">
                    <img src="./Café Bliss_files/photo-1608070734668-e74dc3dda037" alt="Latte">
                    <h3>Latte</h3>
                    <p>₹200</p>
                    <button onclick="addToOrder(&#39;Latte&#39;, 200)">Order</button>
                </div>
                <div class="menu-item">
                    <img src="./Café Bliss_files/photo-1633941012017-d5d8a24e8306" alt="Cappuccino">
                    <h3>Cappuccino</h3>
                    <p>₹200</p>
                    <button onclick="addToOrder(&#39;Cappuccino&#39;, 200)">Order</button>
                </div>
                <div class="menu-item">
                    <img src="./Café Bliss_files/photo-1621221815216-4fd79da6c48c" alt="Mocha">
                    <h3>Mocha</h3>
                    <p>₹250</p>
                    <button onclick="addToOrder(&#39;Mocha&#39;, 250)">Order</button>
                </div>
                <div class="menu-item">
                    <img src="./Café Bliss_files/istockphoto-1221237754-170667a.webp" alt="Chicken Sandwich">
                    <h3>Chicken Sandwich</h3>
                    <p>₹300</p>
                    <button onclick="addToOrder(&#39;Chicken Sandwich&#39;, 300)">Order</button>
                </div>
                <div class="menu-item">
                    <img src="./Café Bliss_files/istockphoto-1085139228-170667a.webp" alt="Veggie Sandwich">
                    <h3>Veggie Sandwich</h3>
                    <p>₹250</p>
                    <button onclick="addToOrder(&#39;Veggie Sandwich&#39;, 250)">Order</button>
                </div>
               
                
                <div class="menu-item">
                    <img src="./Café Bliss_files/istockphoto-1414575281-170667a.webp" alt="Margherita Pizza">
                    <h3>Margherita Pizza</h3>
                    <p>₹400</p>
                    <button onclick="addToOrder(&#39;Margherita Pizza&#39;, 400)">Order</button>
                </div>
                <div class="menu-item">
                    <img src="./Café Bliss_files/istockphoto-1043604390-170667a.webp" alt="Chicken Pizza">
                    <h3>Chicken Pizza</h3>
                    <p>₹450</p>
                    <button onclick="addToOrder(&#39;Chicken Pizza&#39;, 450)">Order</button>
                </div>
            </div>
        </div>
    </section>

    <div id="order-summary">
        <h2>Order Summary</h2>
        <ul id="order-list"></ul>
        <p>Total: ₹<span id="total-amount">0</span></p>
    </div>

    <footer>
        <div class="container">
            <p>© 2024 Café Bliss. All rights reserved.</p>
        </div>
    </footer>

    <script>
        let totalAmount = 0;
        const orderList = document.getElementById('order-list');
        const totalAmountElement = document.getElementById('total-amount');

        function addToOrder(itemName, itemPrice) {
            const orderItem = document.createElement('li');
            orderItem.textContent = `${itemName} - ₹${itemPrice}`;
            orderList.appendChild(orderItem);
            totalAmount += itemPrice;
            totalAmountElement.textContent = totalAmount;
        }
    </script>
<!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>


</body></html>
