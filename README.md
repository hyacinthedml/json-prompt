Extract all data from the image/document below.

Return ONLY a valid JSON object with this exact structure:
{
  "data_type": "invoice | chart | table | form",
  "extracted_data": {
    "field_name": "value",
    "field_name_2": "value_2"
  },
  "data_points": [
    {"label": "item1", "value": "value1"},
    {"label": "item2", "value": "value2"}
  ],
  "notes": "Any fields that were unclear or null values, explain here"
}

Do not include any text outside the JSON. Return ONLY the JSON object.
If a value is unclear, use null and explain in "notes".
