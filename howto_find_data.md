---
title: How to Find Data
parent: Tutorials
has_children: false
nav_order: 2
---

# How to Find Data in the NF Data Portal

This example will focus on the Studies section and walk though a number of different ways to search for data. Each method for searching can be used by itself or combined.
1. Go to [nf.synapse.org](https://nf.synapse.org/).
2. Click the **Explore** button under Studies.
![Navigating to Explore Studies on the NF Data Portal home page, under Portal Programs and Goals.](https://nf-osi.github.io/assets/images/howtofind_portalprograms_explorestudies.png) 
You can also visit this page directly at: [https://nf.synapse.org/Explore/Studies](https://nf.synapse.org/Explore/Studies)
3. **Exploring with the search bar.** Click on the search icon on the right-hand side of the page to reveal a search function.  
![Using the search bar to explore studies.](https://nf-osi.github.io/assets/images/howtofind_explorestudies.png) 
  * To find studies on plexiform neurofibromas, type ‘plexiform’ into the search bar and select the  ‘Summary’ field — the summary field is typically a study abstract or summary. You could also search the ‘Study Name’ field.
![Conducting a search in the search bar](https://nf-osi.github.io/assets/images/howtofind_explorestudies_search.png) 
  * Notice that the visualizations and corresponding study list below will update to reflect only studies that match your search criteria.     
4. **Exploring with visualizations.** Hover your mouse over any of  the charts displayed at the top of the page to view their components. Click on a section of interest, such as studies where study status is ‘Completed.’
![Using the graphs / visualiations to narrow a search.](https://nf-osi.github.io/assets/images/howtofind_explorestudies_graphs.png) 
  * This will create an additional filter for your search results from Step 3, displaying only completed studies containing the term “plexiform” in the study summary. Scroll down to browse the list of studies.
  * Note that you can select multiple slices of a single pie chart at once by clicking on them.  To deselect a slice, simply click on it again.
5. Exploring with filters. For an additional layer of filtering, use the sidebar on the left. Scroll down to the Data Status section and select  ‘Published’ by checking the box next to ‘Published.’  Notice that the visualizations and study list have updated again to reflect this new filter. 
![Filtering with the sidebar.](https://nf-osi.github.io/assets/images/howtofind_filter_published.png) 
6. If you want to conduct a new search, deselect any of your previous filters (x) before starting again. If you wish to share your search results with a collaborator, copy the url — see the above search at this [URL](https://nf.synapse.org/Explore/Studies?QueryWrapper0=%7B%22sql%22%3A%22SELECT%20*%20FROM%20syn16787123%22%2C%22limit%22%3A25%2C%22offset%22%3A0%2C%22additionalFilters%22%3A%5B%7B%22columnName%22%3A%22summary%22%2C%22operator%22%3A%22LIKE%22%2C%22values%22%3A%5B%22%25plexiform%25%22%5D%2C%22concreteType%22%3A%22org.sagebionetworks.repo.model.table.ColumnSingleValueQueryFilter%22%7D%5D%2C%22selectedFacets%22%3A%5B%7B%22concreteType%22%3A%22org.sagebionetworks.repo.model.table.FacetColumnValuesRequest%22%2C%22columnName%22%3A%22studyStatus%22%2C%22facetValues%22%3A%5B%22Completed%22%5D%7D%2C%7B%22concreteType%22%3A%22org.sagebionetworks.repo.model.table.FacetColumnValuesRequest%22%2C%22columnName%22%3A%22dataStatus%22%2C%22facetValues%22%3A%5B%22Published%22%5D%7D%5D%7D) — at the top of your page to preserve your filters. 

### Related Documentation
* [Finding and Downloading Files (Programatically)](https://user-guides.synapse.org/articles/downloading_data.html#finding-and-downloading-files)
