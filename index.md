---
Title: PDQ Project
Layout: layout.liquid
---

<pdq-json id="holiday-data">
<script type="application/json" slot="json">
[
  {
    "name": "Alice",
    "age": 25
  },
  {
    "name": "Bob",
    "age": 30
  },
  {
    "name": "Charley",
    "age": 30
  }
]

<pdq-data-request id="posts-data" url="https://www.gov.uk/bank-holidays.json"></pdq-data-request>
<pdq-table id="bank-holidays" source="holiday-data"></pdq-table>
<pdq-perspective-viewer height="220px" table="bank-holidays" slicers='["title", "date"]'></pdq-perspective-viewer>

</script>
</pdq-json>



