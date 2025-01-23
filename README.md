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
            margin-top: 0px;
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
            color: #333;
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
        <b>
        <h1>OSINT Framework</h1>
        <p>Explore tools for Open Source Intelligence</p>
        </b>
    </header>

    <main>
        <div class="card">
            <div class="text">
            <h2><a href="https://nslookup.com" target="_blank">IP Address</a></h2>
            <p align="justify">
                An A record (Address Record) points a domain or subdomain to an IP address. 
                For example, an A Record is used to point a logical domain name, such as "google.com," to the IP address of Google's
                 hosting server, "74.125.224.147".
            <p>=> CNAME Record
            <p>=> MX Record
            <p>=> TXT Record
            <p>=> SRV Recprd
            <p>=> AAAA Record
            </div>
            <img class="hi" src="https://ruurtjan.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fdns-lookup.5814af55.png&w=3840&q=75"
        alt="IP Address Logo">
    </p> </p> </p> </p> </p> </p> </p> 
        </div>
        

        <div class="card">
            <div class="text">
            <h2><a href="https://www.whois.com/whois/" target="_blank">Domain Register Record Information</a></h2>
            <p align="justify">A Whois domain lookup allows you to trace the ownership and tenure of a domain name. 
                imilar to how all houses are registered with a governing authority, all domain name registries maintain a record of 
                information about every domain name purchased through them, along with who owns it, and the date till which it has 
                been purchased.<br>
                <p>=> Useful for:

                     <p>*Investigating domain history.
                        <p>*Verifying domain ownership. 
                            <p>*Checking domain availability.
            </div>
                <img src="https://jamesnames.com/wp-content/uploads/2021/06/Screen-Shot-2021-06-03-at-13.44.16.png"/>
            </p></p></p></p></p>
        </div>
        
        <div class="card">
            <div class="text">
                <h2><a href="https://haveibeenpwned.com/" target="_blank">Email Address in Data Breach</a></h2>
                <p align="justify">Have I Been Pwned? is a website that allows Internet users to check whether their personal data has 
                    been compromised by data breaches. The site has been widely touted as a valuable resource for Internet users wishing
                     to protect their own security and privacy.
                     <p>=> Useful for:
                        <p>*Protecting personal information by identifying risks early.
                            <p>*Encouraging password updates and better security practices.
                                <p>*Helping cybersecurity professionals investigate breaches.
            </div>
                <img src="https://i.dailymail.co.uk/i/pix/2017/08/07/11/430B10E400000578-0-image-a-32_1502101523740.jpg">
            </p></p></p></p></p>
        </div>

        <div class="card">
            <div class="text">
                <h2><a href="https://wheregoes.com/" target="_blank">4. URL Redirect Checker</a></h2>
                <p align="justify">Where does this link go? The URL redirect checker follows the path of the URL. It will show you the 
                    full redirection path of URLs, shortened links, or tiny URLs. Also referred to as a link checker, url checker, 
                    redirect checker, link tracker, url tracker, redirect tracer, link follower, 301 redirect checker, redirect tracker, 
                    URL tester, and so on.
                    <p>=> USeful for:
                        <p>* Identifying network issues such as slow connections or routing problems.
                            <p>*Troubleshooting internet and network performance.
                                <p>*Helping network administrators optimize paths and reduce latency.
                </div>
                <img src="https://preview.atlaq.com/fe6992e5ec47e4acdac3596b81339dec_wheregoes.com.png">
            </p></p></p></p></p>
                </div>

         <div class="card">
            <div class="text">
                <h2><a href="https://www.virustotal.com/gui/home/upload" target="_blank">5. Malware Analyse</a></h2>
                <p align="justify">Analyse suspicious files, domains, IPs and URLs to detect malware and other breaches, automatically 
                    share them with the security community. 
                    <p>=> Useful for:
                        <p>*Checking suspicious files and URLs before opening them.
                            <p>*Helping security professionals detect and analyze malware.
                                <p>*Verifying if a website or file is safe to use.
                                    <p>*Assisting in digital forensics and incident response.
                </div>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRJGre-guJVmHN1wzxroKQwR8W0YXsPZ3KMwg&s">
            </p></p></p></p></p></p>
                </div>

         <div class="card">
            <div class="text">
                <h2> <a href = "https://tineye.com/" target="_blank">6. Reverse Image Search</a></h2>
                <p align="justify">TinEye is a reverse image search engine developed and offered by Idée, Inc., a company based in Toronto, Ontario,
                    Canada. It is the first image search engine on the web to use image identification technology rather than keywords, 
                    metadata or watermarks.
                    <p>=> Useful for:
                        <p>*Checking if images are being used without permission or illegally.
                            <p>*Finding higher quality versions of an image.
                                <p>*Assisting in digital forensics and copyright investigations.
                </div>
                <img src="https://www.zdnet.com/a/img/resize/ac1826854692901fe788f26638f8074f39808639/2016/07/31/f436de30-3f53-4f2c-8c4b-99fc5a9888f4/ziff-tineye.jpg?auto=webp&width=1280">
            </p></p></p></p></p>
                </div>

      
    </main>

    <footer>
        <b>
        <hr>
        <p class="special"><i>By</i></p> 
        <p class="special"><i>Nitharshana N</i></p>
        <p class="special"><i>Tharani C</i></p>
        <p class="special"><i>Lithika V</i></p>
        <p><i>Reference:<u><a href="https://framework.com" >osintframework.com</a></u></i></p>
        <h2>&copy; <i>Copyright</i></h2></b>
    </footer>
</body>
</html>
