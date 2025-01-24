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

        .card ul {
            text-align: left;
            color: white;
            padding-left: 20px;
        }

        .card p {
            margin: 10px 0 0;
            font-size: 1em;
            font-style: italic;
            color: white;
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
                <h2><a href="https://nslookup.com" target="_blank">1. IP Address</a></h2>
                <p>An A record (Address Record) points a domain or subdomain to an IP address.</p>
                <ul>
                    <li>CNAME Record</li>
                    <li>MX Record</li>
                    <li>TXT Record</li>
                    <li>SRV Record</li>
                    <li>AAAA Record</li>
                </ul>
            </div>
            <img src="https://ruurtjan.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fdns-lookup.5814af55.png&w=3840&q=75" alt="IP Address Illustration">
        </div>

        <!-- Card 2 -->
        <div class="card">
            <div class="text">
                <h2><a href="https://www.whois.com/whois/" target="_blank">2. Domain Register Record Information</a></h2>
                <p>Allows tracing of domain ownership and history.</p>
                <ul>
                    <li>Investigating domain history</li>
                    <li>Verifying domain ownership</li>
                    <li>Checking domain availability</li>
                </ul>
            </div>
            <img src="https://jamesnames.com/wp-content/uploads/2021/06/Screen-Shot-2021-06-03-at-13.44.16.png" alt="Whois Lookup Tool">
        </div>

        <!-- Card 3 -->
        <div class="card">
            <div class="text">
                <h2><a href="https://haveibeenpwned.com/" target="_blank">3. Email Address in Data Breach</a></h2>
                <p>Check if your email was part of a data breach.</p>
                <ul>
                    <li>Protect personal information</li>
                    <li>Encourage password updates</li>
                    <li>Investigate breaches</li>
                </ul>
            </div>
            <img src="https://i.dailymail.co.uk/i/pix/2017/08/07/11/430B10E400000578-0-image-a-32_1502101523740.jpg" alt="Data Breach Illustration">
        </div>

        <!-- Card 4 -->
        <div class="card">
            <div class="text">
                <h2><a href="https://wheregoes.com/" target="_blank">4. URL Redirect Checker</a></h2>
                <p>Trace the redirection path of a URL.</p>
                <ul>
                    <li>Identify network issues</li>
                    <li>Troubleshoot performance</li>
                    <li>Optimize paths</li>
                </ul>
            </div>
            <img src="https://preview.atlaq.com/fe6992e5ec47e4acdac3596b81339dec_wheregoes.com.png" alt="Redirect Checker Illustration">
        </div>

        <!-- Card 5 -->
        <div class="card">
            <div class="text">
                <h2><a href="https://www.virustotal.com/gui/home/upload" target="_blank">5. Malware Analysis</a></h2>
                <p>Analyze suspicious files, domains, and URLs for malware.</p>
                <ul>
                    <li>Check files and URLs before opening</li>
                    <li>Detect and analyze malware</li>
                    <li>Assist in digital forensics</li>
                </ul>
            </div>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRJGre-guJVmHN1wzxroKQwR8W0YXsPZ3KMwg&s" alt="Malware Analysis Illustration">
        </div>

        <!-- Card 6 -->
        <div class="card">
            <div class="text">
                <h2><a href="https://tineye.com/" target="_blank">6. Reverse Image Search</a></h2>
                <p>Search for image origins or higher resolutions.</p>
                <ul>
                    <li>Find higher-quality images</li>
                    <li>Identify unauthorized use</li>
                    <li>Assist in copyright investigations</li>
                </ul>
            </div>
            <img src="https://www.zdnet.com/a/img/resize/ac1826854692901fe788f26638f8074f39808639/2016/07/31/f436de30-3f53-4f2c-8c4b-99fc5a9888f4/ziff-tineye.jpg?auto=webp&width=1280" alt="Reverse Image Search Illustration">
        </div>
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
