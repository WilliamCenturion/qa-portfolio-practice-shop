

# Bug Reports — Practice Software Testing

## BUG-002 — Inconsistent Category Filtering

- **Application:** Practice Software Testing
- **Module:** Product Catalog
- **Severity:** Medium (provisional)
- **Priority:** Medium (provisional)
- **Status:** Under Investigation

### Description

Category filtering behaved inconsistently during exploratory testing. The `hand tools` category initially failed to filter the product list, while another category worked.

Refreshing the page restored filter functionality.

### Steps to Reproduce

1. Open the product catalog.
2. Select the `hand tools` category.
3. Observe the displayed products.
4. Refresh the page.
5. Apply the category filter again.

### Expected Result

Only products belonging to the selected category should be displayed consistently, without requiring a page refresh.

### Actual Result

The category filter initially failed to behave as expected. After refreshing the page, filtering worked again.

### Additional Observations

- Price sorting in ascending and descending order worked.
- Another category worked during testing.
- The combined filter and sorting scenario failed when filtering did not work.
- The root cause has not been determined.

### Evidence

Screenshot captured during exploratory testing. Evidence should be attached to the repository when available.

### Related Test Area

Product catalog filtering and regression testing.
