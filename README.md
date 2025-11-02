🌐 ASP.NET Web Forms App — GetFriendlyUrlSegments Example

A sample ASP.NET Web Forms application demonstrating how to use the GetFriendlyUrlSegments method to handle clean, user-friendly URLs.
This project showcases how to make Web Forms applications more readable and SEO-friendly without changing the underlying routing logic.

-----------------------------

🚀 Features

🧩 Friendly URL Routing — Converts query strings into path-based URLs

📡 Dynamic URL Segment Handling using GetFriendlyUrlSegments()

💡 Backward Compatibility — Works with traditional Web Forms structure

📜 Simple Configuration — Easy to integrate into any Web Forms project

⚙️ Clean and SEO-Friendly URLs

--------------------

🧩 Technologies Used
| Component            | Description          |
| -------------------- | -------------------- |
| **Framework**        | ASP.NET Web Forms    |
| **Language**         | C#                   |
| **Routing**          | ASP.NET FriendlyUrls |
| **IDE**              | Visual Studio        |
| **Target Framework** | .NET Framework 4.5+  |

-------------------

🧠 How It Works

Friendly URLs Enabled:
RouteTable.Routes.EnableFriendlyUrls() activates clean routing.

URL Parsing:
The GetFriendlyUrlSegments() method retrieves path segments after the page name.

Dynamic Data Handling:
You can use the segment values for loading records, filtering data, or handling user actions dynamically.

-----------------------

🧠 Future Enhancements

🔄 Add multiple segment parsing (e.g., /Products/101/Reviews)

📡 Integrate with a database for real-time data retrieval

🧭 Add custom route mappings

💾 Include URL rewriting for legacy query-based links
