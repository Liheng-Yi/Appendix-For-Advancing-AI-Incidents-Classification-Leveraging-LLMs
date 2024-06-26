## Appendix D: Tree of Thought Framework Classification Results

The Tree of Thoughts framework allows the LLM to explore various reasoning
paths and collectively determine the most well-supported classification based on
the text of the article text.


```json

{
    "1": {
        "Country": "Worldwide",
        "State": "",
        "City": "",
        "Continent": "Worldwide",
        "Company": "YouTube",
        "Company city": "San Bruno",
        "Company state": "California",
        "Affected population": [
            "Student",
            "Online Female Population",
            "Twitter Users"
        ],
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Classes of irresponsible AI use": [
            "Human Incompetence",
            "Disinformation",
            "Mental Health",
            "Other"
        ],
        "Subclasses": {
            "Human Incompetence": [
                "Technical"
            ],
            "Disinformation": [
                "Textual",
                "Image",
                "Video"
            ],
            "Mental Health": [],
            "Other": []
        },
        "Sub-subclass": [],
        "Area of AI Application": "content filtering",
        "Online": "yes"
    },
    "2": {
        "Country": "United States",
        "State": "New Jersey",
        "City": "Robbinsville",
        "Continent": "North America",
        "Company": "Amazon",
        "Company city": "Seattle",
        "Company state": "Washington",
        "Affected population": [
            "Warehouse Workers"
        ],
        "Number of people actually affected": "24",
        "Number of people potentially affected": "54",
        "Classes of irresponsible AI use": [
            "Human Incompetence"
        ],
        "Subclasses": {
            "Human Incompetence": [
                "Technical"
            ]
        },
        "Sub-subclass": [],
        "Area of AI Application": "Warehouse automation",
        "Online": "no"
    },
    "3": {
        "Country": "Indonesia",
        "State": "",
        "City": "Jakarta",
        "Continent": "Asia",
        "Company": "Boeing",
        "Company city": "Chicago",
        "Company state": "Illinois",
        "Affected population": [
            "Air Travelers"
        ],
        "Number of people actually affected": "189",
        "Number of people potentially affected": "Unknown",
        "Classes of irresponsible AI use": [
            "Human Incompetence",
            "Other"
        ],
        "Subclasses": {
            "Human Incompetence": [
                "Technical"
            ],
            "Other": []
        },
        "Sub-subclass": {
            "Technical": []
        },
        "Area of AI Application": "Aviation safety and control systems",
        "Online": "no"
    },
    "4": {
        "Country": "USA",
        "State": "Arizona",
        "City": "Tempe",
        "Continent": "North America",
        "Company": "Uber",
        "Company city": "San Francisco",
        "Company state": "California",
        "Affected population": [
            "Pedestrians"
        ],
        "Number of people actually affected": "1",
        "Number of people potentially affected": "Unknown",
        "Classes of irresponsible AI use": [
            "Human Incompetence",
            "Other"
        ],
        "Subclasses": {
            "Human Incompetence": [
                "Technical"
            ],
            "Other": []
        },
        "Sub-subclass": [],
        "Area of AI Application": "Autonomous Vehicles",
        "Online": "no"
    },
    "5": {
        "Country": "United States",
        "State": "",
        "City": "",
        "Continent": "North America",
        "Company": "Not specified",
        "Company city": "Not specified",
        "Company state": "",
        "Affected population": [
            "Patients undergoing robotic surgery"
        ],
        "Number of people actually affected": "1535",
        "Number of people potentially affected": "1.7 million",
        "Classes of irresponsible AI use": [
            "Human Incompetence",
            "Technical"
        ],
        "Subclasses": {
            "Human Incompetence": [
                "Technical"
            ]
        },
        "Sub-subclass": [],
        "Area of AI Application": "Robotic surgery",
        "Online": "no"
    },
    "6": {
        "Country": "Worldwide",
        "State": "",
        "City": "",
        "Continent": "Worldwide",
        "Company": "Microsoft",
        "Company city": "Redmond",
        "Company state": "Washington",
        "Affected population": [
            "Twitter Users",
            "Online Population"
        ],
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Classes of irresponsible AI use": [
            "Human Incompetence",
            "Disinformation",
            "Other"
        ],
        "Subclasses": {
            "Human Incompetence": [
                "Technical"
            ],
            "Disinformation": [
                "Textual"
            ],
            "Other": []
        },
        "Sub-subclass": [],
        "Area of AI Application": "Social Media Interaction",
        "Online": "yes"
    },
    "7": {
        "Country": "Worldwide",
        "State": "",
        "City": "",
        "Continent": "Worldwide",
        "Company": "Wikipedia",
        "Company city": "San Francisco",
        "Company state": "California",
        "Affected population": [
            "Online Users"
        ],
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Classes of irresponsible AI use": [
            "Human Incompetence",
            "Other"
        ],
        "Subclasses": {
            "Human Incompetence": [
                "Technical"
            ],
            "Other": []
        },
        "Sub-subclass": [],
        "Area of AI Application": "Content management and editing",
        "Online": "yes"
    },
    "8": {
        "Country": "United States",
        "State": "California",
        "City": "San Francisco",
        "Continent": "North America",
        "Company": "Uber",
        "Company city": "San Francisco",
        "Company state": "California",
        "Affected population": [
            "General Public",
            "Bicyclists",
            "Pedestrians"
        ],
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Classes of irresponsible AI use": [
            "Human Incompetence",
            "Other"
        ],
        "Subclasses": {
            "Human Incompetence": [
                "Technical"
            ],
            "Other": []
        },
        "Sub-subclass": {
            "Technical": []
        },
        "Area of AI Application": "Autonomous Vehicles",
        "Online": "no"
    },
    "9": {
        "Country": "United States",
        "State": "New York",
        "City": "New York City",
        "Continent": "North America",
        "Company": "New York City Department of Education",
        "Company city": "New York City",
        "Company state": "New York",
        "Affected population": [
            "Student",
            "Teachers"
        ],
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Classes of irresponsible AI use": [
            "Human Incompetence",
            "Other"
        ],
        "Subclasses": {
            "Human Incompetence": [
                "Administrative"
            ],
            "Other": []
        },
        "Sub-subclass": [],
        "Area of AI Application": "Educational assessment",
        "Online": "yes"
    },
    "10": {
        "Country": "United States",
        "State": "",
        "City": "",
        "Continent": "North America",
        "Company": "Starbucks",
        "Company city": "Seattle",
        "Company state": "Washington",
        "Affected population": [
            "Retail Workers",
            "Single Parents",
            "Students"
        ],
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Classes of irresponsible AI use": [
            "Human Incompetence",
            "Discrimination"
        ],
        "Subclasses": {
            "Human Incompetence": [
                "Technical"
            ],
            "Discrimination": [
                "Data bias"
            ]
        },
        "Sub-subclass": {
            "Technical": [],
            "Data bias": [
                "Economic",
                "Other"
            ]
        },
        "Area of AI Application": "Workforce management",
        "Online": "yes"
    },
    "11": {
        "Country": "United States",
        "State": "Florida",
        "City": "Broward County",
        "Continent": "North America",
        "Company": "Northpointe (now part of Equivant)",
        "Company city": "Canton",
        "Company state": "Ohio",
        "Affected population": [
            "Black Defendants",
            "White Defendants"
        ],
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Classes of irresponsible AI use": [
            "Discrimination"
        ],
        "Subclasses": {
            "Discrimination": [
                "Data bias",
                "Algorithmic bias"
            ]
        },
        "Sub-subclass": {
            "Data bias": [
                "Race",
                "Gender"
            ],
            "Algorithmic bias": [
                "Feedback loop",
                "Optimization function"
            ]
        },
        "Area of AI Application": "Criminal justice risk assessments",
        "Online": "yes"
    },
    "12": {
        "Country": "",
        "State": "",
        "City": "",
        "Continent": "",
        "Company": "",
        "Company city": "",
        "Company state": "",
        "Affected population": [],
        "Number of people actually affected": "",
        "Number of people potentially affected": "",
        "Classes of irresponsible AI use": [],
        "Subclasses": {},
        "Sub-subclass": [],
        "Area of AI Application": "",
        "Online": ""
    },
    "13": {
        "Country": "United States",
        "State": "",
        "City": "",
        "Continent": "North America",
        "Company": "Google's Alphabet",
        "Company city": "Mountain View",
        "Company state": "California",
        "Affected population": [
            "Online Population"
        ],
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Classes of irresponsible AI use": [
            "Discrimination",
            "Human Incompetence"
        ],
        "Subclasses": {
            "Discrimination": [
                "Data bias",
                "Algorithmic bias"
            ],
            "Human Incompetence": [
                "Technical"
            ]
        },
        "Sub-subclass": {
            "Data bias": [
                "Gender",
                "Race",
                "Sexual Orientation"
            ],
            "Algorithmic bias": [
                "Other"
            ]
        },
        "Area of AI Application": "content filtering",
        "Online": "yes"
    },
    "14": {
        "Country": "Worldwide",
        "State": "",
        "City": "",
        "Continent": "Worldwide",
        "Company": "Google",
        "Company city": "Mountain View",
        "Company state": "California",
        "Affected population": [
            "Online Population"
        ],
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Classes of irresponsible AI use": [
            "Discrimination"
        ],
        "Subclasses": {
            "Discrimination": [
                "Data bias"
            ]
        },
        "Sub-subclass": {
            "Data bias": [
                "Gender",
                "Race",
                "Sexual Orientation"
            ]
        },
        "Area of AI Application": "Natural Language Processing",
        "Online": "yes"
    },
    "15": {
        "Country": "Worldwide",
        "State": "",
        "City": "",
        "Continent": "Worldwide",
        "Company": "Amazon.com",
        "Company city": "Seattle",
        "Company state": "Washington",
        "Affected population": [
            "LGBTQ"
        ],
        "Number of people actually affected": "Unknown",
        "Number of people potentially affected": "Unknown",
        "Classes of irresponsible AI use": [
            "Discrimination",
            "Human Incompetence"
        ],
        "Subclasses": {
            "Discrimination": [
                "Data bias"
            ],
            "Human Incompetence": [
                "Technical"
            ]
        },
        "Sub-subclass": {
            "Data bias": [
                "Sexual Orientation"
            ]
        },
        "Area of AI Application": "Content filtering",
        "Online": "yes"
    }
}
```