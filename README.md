<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OSINT Framework</title>
    <style>
        body {
            display: grid;
            place-items: center;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: lightskyblue;
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: #007BFF;
            color: black;
            font-family: 'Times New Roman', Times, serif;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            margin: 0;
            font-size: 1.2em;
        }

        .container {
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            align-items: flex-start;
            gap: 20px;
        }

        .card {
            flex: 1;
            display: flex;
            justify-content: space-between;
            background-color: rgb(5, 90, 90);
            padding: 20px;
            width: 80%;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            text-align: center;
        }

        .card img {
            height: 250px;
            margin-left: 10px;
        }

        .hi {
            height: 250px;
            margin-left: 10px;
            margin-top: 0;
        }

        .card h2 {
            margin: 0;
            font-family: 'Times New Roman', Times, serif;
            font-size: 1.5em;
            color: #007BFF;
        }

        .card h2 a {
            text-decoration: none;
            color: #007BFF;
        }

        .card h4 {
            color: white;
        }

        .card p {
            margin: 10px 0 0;
            font-size: 1em;
            font-style: italic;
            color: white;
        }

        .card ul {
            text-align: left;
            color: white;
            padding-left: 20px;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #007BFF;
            color: black;
            margin-top: 20px;
            font-family: 'Times New Roman', Times, serif;
        }
    </style>
</head>
<body>
    <header>
        <h1>OSINT Framework</h1>
        <p>Explore tools for Open Source Intelligence</p>
    </header>

    <main>
        <!-- Card 1 -->
        <div class="card">
            <div class="text">
                <h2><a href="https://nslookup.com" target="_blank">IP Address</a></h2>
                <p>An A record (Address Record) points a domain or subdomain to an IP address. For example, an A Record is used to point a logical domain name, such as "google.com," to the IP address of Google's hosting server, "74.125.224.147".</p>
                <ul>
                    <li>CNAME Record</li>
                    <li>MX Record</li>
                    <li>TXT Record</li>
                    <li>SRV Record</li>
                    <li>AAAA Record</li>
                </ul>
            </div>
            <img class="hi" src="https://ruurtjan.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fdns-lookup.5814af55.png&w=3840&q=75" alt="IP Address Illustration">
        </div>

        <!-- Card 2 -->
        <div class="card">
            <div class="text">
                <h2><a href="https://www.whois.com/whois/" target="_blank">Domain Register Record Information</a></h2>
                <p>A Whois domain lookup allows you to trace the ownership and tenure of a domain name. Similar to how all houses are registered with a governing authority, all domain name registries maintain a record of information about every domain name purchased through them, along with who owns it, and the date till which it has been purchased.</p>
                <ul>
                    <li>Investigating domain history</li>
                    <li>Verifying domain ownership</li>
                    <li>Checking domain availability</li>
                </ul>
            </div>
            <img src="https://jamesnames.com/wp-content/uploads/2021/06/Screen-Shot-2021-06-03-at-13.44.16.png" alt="Whois Lookup Tool">
        </div>

        <!-- Additional cards omitted for brevity -->
    </main>

    <footer>
        <hr>
        <p><i>By</i></p>
        <p><i>Nitharshana N</i></p>
        <p><i>Tharani C</i></p>
        <p><i>Lithika V</i></p>
        <p><i>Reference: <a href="https://framework.com" target="_blank">osintframework.com</a></i></p>
        <h2>&copy; <i>Copyright</i></h2>
    </footer>
</body>
</html>

