# 🎯 AI Lead Generation Agent - Powered by Firecrawl's Extract Endpoint

The **AI Lead Generation Agent** automates the process of finding and qualifying potential leads from Quora. It leverages Firecrawl's search and the new Extract endpoint to identify relevant user profiles, extract valuable information, and organize it into a structured format in Google Sheets.

This tool helps sales and marketing teams efficiently build targeted lead lists while saving hours of manual research.

---

## 🚀 Features

- **Targeted Search**  
  Uses Firecrawl's search endpoint to find relevant Quora URLs based on your search criteria.

- **Intelligent Extraction**  
  Leverages Firecrawl's new Extract endpoint to pull detailed user information from Quora profiles.

- **Automated Processing**  
  Formats extracted user information into a clean, structured format ready for analysis.

- **Google Sheets Integration**  
  Automatically creates and populates Google Sheets with lead information for easy sharing and collaboration.

- **Customizable Criteria**  
  Define specific search parameters to find your ideal leads tailored to your niche or campaign.

---

## 🛠️ How to Get Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/ai-lead-generation-agent.git
cd ai-lead-generation-agent
````

### 2. Set Up Environment Variables

Create a `.env` file in the root directory and add your Firecrawl API key and Google Sheets credentials:

```
FIRECRAWL_API_KEY=your_firecrawl_api_key
GOOGLE_SHEETS_CREDENTIALS=path_to_your_google_credentials.json
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Search Criteria

Edit the `config.yaml` file to customize your Quora search parameters such as keywords, topics, or locations.

### 5. Run the Agent

```bash
python lead_generation_agent.py
```

---

## 📈 What Happens Next?

* The agent will use Firecrawl's search endpoint to find Quora user profiles matching your criteria.
* It will extract relevant user details (name, bio, activity, etc.) using the Extract endpoint.
* Data will be automatically formatted and uploaded to a new Google Sheet.
* You receive a sharable link to your organized lead list, ready for your sales or marketing outreach!

---

## 🔧 Customization

You can tweak the following parameters to fit your needs:

| Parameter     | Description                      | Example                  |
| ------------- | -------------------------------- | ------------------------ |
| `keywords`    | Search terms to find leads       | `"machine learning"`     |
| `location`    | Filter leads by location         | `"United States"`        |
| `max_results` | Limit number of leads extracted  | `50`                     |
| `sheet_name`  | Name of the Google Sheet created | `"ML Leads - July 2025"` |

---

## 📚 Additional Resources

* [Firecrawl API Documentation](https://firecrawl.com/docs)
* [Google Sheets API Guide](https://developers.google.com/sheets/api)
* [Quora Website](https://www.quora.com)

---

## 🤝 Contributing

Feel free to open issues or submit pull requests to improve this agent. Suggestions and feature requests are very welcome!

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Need Help?

If you encounter any issues or have questions, please open an issue on GitHub or contact me at \[your email].

---

⭐ **Enjoy using the AI Lead Generation Agent!** ⭐
___________________________________________
