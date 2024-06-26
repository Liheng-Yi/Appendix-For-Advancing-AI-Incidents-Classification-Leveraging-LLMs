## Appendix C: Few-Shot Learning Classification Results

These are the classification results of 17 incidents from GPT-4 with two-shot
prompting with Chain-of-Thought (CoT) technique.

```json
{
    "1": {
        "Country": "Global",
        "State": "N/A",
        "City": "N/A",
        "Continent": "Global",
        "Company": "Google LLC",
        "Company city": "Mountain View, CA",
        "Affected population": "Children",
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Class of irresponsible AI use": [
            "Disinformation",
            "Human Incompetence",
            "Mental Health",
            "Other"
        ],
        "Subclasses": [
            "Disinformation-> Video",
            "Human Incompetence-> Technical",
            "Mental Health-> Psychological Impact",
            "Other-> Inappropriate Content"
        ],
        "Sub-subclass": [],
        "Area of AI Application": "Video Sharing/Streaming",
        "Online": "Yes"
    },
    "2": {
        "Country": "United States",
        "State": "New Jersey",
        "City": "Robbinsville",
        "Continent": "North America",
        "Company": "Amazon",
        "Company city": "Seattle, WA",
        "Affected population": "Amazon workers",
        "Number of people actually affected": "24",
        "Number of people potentially affected": "54",
        "Class of irresponsible AI use": [
            "Human Incompetence"
        ],
        "Subclasses": [
            "Human Incompetence-> Technical"
        ],
        "Sub-subclass": [],
        "Area of AI Application": "warehouse automation, robotics",
        "Online": "No"
    },
    "3": {
        "Country": "Indonesia",
        "State": "",
        "City": "Jakarta",
        "Continent": "Asia",
        "Company": "Boeing",
        "Company city": "Chicago, IL",
        "Affected population": "Airline passengers and crew",
        "Number of people actually affected": "189",
        "Number of people potentially affected": "Unknown",
        "Class of irresponsible AI use": [
            "Human Incompetence"
        ],
        "Subclasses": [
            "Human Incompetence-> Technical"
        ],
        "Sub-subclass": [],
        "Area of AI Application": "Aviation safety systems",
        "Online": "No"
    },
    "4": {
        "Country": "United States",
        "State": "Arizona",
        "City": "Tempe",
        "Continent": "North America",
        "Company": "Uber",
        "Company city": "San Francisco, CA",
        "Affected population": "Pedestrians",
        "Number of people actually affected": "1",
        "Number of people potentially affected": "Unknown",
        "Class of irresponsible AI use": [
            "Human Incompetence",
            "Technical Failure"
        ],
        "Subclasses": [
            "Human Incompetence-> Monitoring Failure",
            "Technical Failure-> Detection Failure"
        ],
        "Sub-subclass": [],
        "Area of AI Application": "autonomous vehicles",
        "Online": "No"
    },
    "5": {
        "Country": "United States",
        "State": "Not specified",
        "City": "Not specified",
        "Continent": "North America",
        "Company": "Not specified",
        "Company city": "Not specified",
        "Affected population": "Patients undergoing robotic surgery",
        "Number of people actually affected": "144 deaths, 1391 injuries",
        "Number of people potentially affected": "More than 1.7 million (number of robotic procedures carried out between 2007 and 2013)",
        "Class of irresponsible AI use": [
            "Human Incompetence",
            "Technical Failure"
        ],
        "Subclasses": [
            "Human Incompetence-> Operator error",
            "Technical Failure-> Device malfunction",
            "Technical Failure-> System error"
        ],
        "Sub-subclass": [
            "Device malfunction-> Electrical sparking",
            "Device malfunction-> Uncontrolled movement",
            "Device malfunction-> Broken pieces",
            "System error-> Loss of video feed"
        ],
        "Area of AI Application": "robotic surgery",
        "Online": "No"
    },
    "6": {
        "Country": "Global",
        "State": "Not specified",
        "City": "Not specified",
        "Continent": "Not specified",
        "Company": "Microsoft",
        "Company city": "Redmond, WA",
        "Affected population": "Twitter Users, Online Community",
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Millions (Twitter user base and wider online community)",
        "Class of irresponsible AI use": [
            "Human Incompetence",
            "Disinformation"
        ],
        "Subclasses": [
            "Human Incompetence-> Lack of foresight",
            "Disinformation-> Racial",
            "Disinformation-> Political",
            "Disinformation-> Gender"
        ],
        "Sub-subclass": [],
        "Area of AI Application": "Social media interaction, Conversational AI",
        "Online": "Yes"
    },
    "7": {
        "Country": "Global",
        "State": "Global",
        "City": "Global",
        "Continent": "Global",
        "Company": "Wikipedia",
        "Company city": "San Francisco, CA",
        "Affected population": "Wikipedia Users",
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Millions",
        "Class of irresponsible AI use": [
            "Human Incompetence"
        ],
        "Subclasses": [
            "Human Incompetence-> Technical"
        ],
        "Sub-subclass": [],
        "Area of AI Application": "Online encyclopedia editing",
        "Online": "Yes"
    },
    "8": {
        "Country": "United States",
        "State": "California",
        "City": "San Francisco",
        "Continent": "North America",
        "Company": "Uber Technologies Inc.",
        "Company city": "San Francisco, CA",
        "Affected population": "General Public",
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Residents and visitors of San Francisco",
        "Class of irresponsible AI use": [
            "Human Incompetence",
            "Other"
        ],
        "Subclasses": [
            "Human Incompetence-> Technical",
            "Other-> Safety"
        ],
        "Sub-subclass": [],
        "Area of AI Application": "autonomous vehicles",
        "Online": "No"
    },
    "9": {
        "Country": "United States",
        "State": "New York",
        "City": "New York City",
        "Continent": "North America",
        "Company": "New York City Department of Education",
        "Company city": "New York, NY",
        "Affected population": "Teachers",
        "Number of people actually affected": "12000",
        "Number of people potentially affected": "Unknown",
        "Class of irresponsible AI use": [
            "Human Incompetence",
            "Other"
        ],
        "Subclasses": [
            "Human Incompetence-> Technical",
            "Other-> Misuse of Data"
        ],
        "Sub-subclass": [],
        "Area of AI Application": "Educational assessment",
        "Online": "Yes"
    },
    "10": {
        "Country": "United States",
        "State": "Various",
        "City": "Various",
        "Continent": "North America",
        "Company": "Starbucks",
        "Company city": "Seattle, WA",
        "Affected population": "Starbucks Workers",
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "130,000 (total number of Starbucks baristas in the U.S.)",
        "Class of irresponsible AI use": [
            "Human Incompetence"
        ],
        "Subclasses": [
            "Human Incompetence-> Technical"
        ],
        "Sub-subclass": [],
        "Area of AI Application": "workforce management, scheduling",
        "Online": "No"
    },
    "11": {
        "Country": "United States",
        "State": "Florida",
        "City": "Broward County",
        "Continent": "North America",
        "Company": "Northpointe (now part of Equivant)",
        "Company city": "Canton, OH",
        "Affected population": "Criminal Defendants",
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Class of irresponsible AI use": [
            "Discrimination",
            "Human Incompetence"
        ],
        "Subclasses": [
            "Discrimination-> Data bias",
            "Discrimination-> Algorithmic bias",
            "Human Incompetence-> Technical"
        ],
        "Sub-subclass": [
            "Data bias-> Race",
            "Data bias-> Gender",
            "Algorithmic bias-> Race",
            "Algorithmic bias-> Gender"
        ],
        "Area of AI Application": "criminal risk assessment",
        "Online": "Yes"
    },
    "12": {
        "Country": "",
        "State": "",
        "City": "",
        "Continent": "",
        "Company": "",
        "Company city": "",
        "Affected population": "",
        "Number of people actually affected": "",
        "Number of people potentially affected": "",
        "Class of irresponsible AI use": [],
        "Subclasses": [],
        "Sub-subclass": [],
        "Area of AI Application": "",
        "Online": ""
    },
    "13": {
        "Country": "Global",
        "State": "N/A",
        "City": "N/A",
        "Continent": "Global",
        "Company": "Google LLC",
        "Company city": "Mountain View, CA",
        "Affected population": "Online Users",
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Millions",
        "Class of irresponsible AI use": [
            "Discrimination"
        ],
        "Subclasses": [
            "Discrimination-> Data bias",
            "Discrimination-> Algorithmic bias"
        ],
        "Sub-subclass": [
            "Data bias-> Race",
            "Data bias-> Sexual Orientation",
            "Data bias-> Economic",
            "Algorithmic bias-> Gender",
            "Algorithmic bias-> Race"
        ],
        "Area of AI Application": "content moderation, online discussion forums",
        "Online": "Yes"
    },
    "14": {
        "Country": "Global",
        "State": "Global",
        "City": "Global",
        "Continent": "Global",
        "Company": "Google LLC",
        "Company city": "Mountain View, CA",
        "Affected population": "Users of Google's Cloud Natural Language API, including developers and indirectly, religious and ethnic minorities",
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Class of irresponsible AI use": [
            "Discrimination"
        ],
        "Subclasses": [
            "Discrimination-> Data bias",
            "Discrimination-> Algorithmic bias"
        ],
        "Sub-subclass": [
            "Data bias-> Race",
            "Data bias-> Sexual Orientation"
        ],
        "Area of AI Application": "Natural Language Processing, Sentiment Analysis",
        "Online": "Yes"
    },
    "15": {
        "1": {
            "Country": "Global",
            "State": "",
            "City": "",
            "Continent": "",
            "Company": "Amazon",
            "Company city": "Seattle, WA",
            "Affected population": "Authors and readers of gay and lesbian-themed books",
            "Number of people actually affected": "Unknown",
            "Number of people potentially affected": "Unknown",
            "Class of irresponsible AI use": [
                "Human Incompetence"
            ],
            "Subclasses": [
                "Human Incompetence-> Technical"
            ],
            "Sub-subclass": [],
            "Area of AI Application": "Online retail, Sales ranking system",
            "Online": "Yes"
        }
    }
}
```
