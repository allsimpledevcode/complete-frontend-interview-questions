# Infinite Scroll

Since there might be a lot of testimonials, you'll have to use the API
endpoint's pagination functionality to repeatedly fetch a limited number of
testimonials at a time. Specifically, the API accepts the following two
query parameters:

- `limit` (required): the maximum number of testimonials to request
- `after` (optional): a string ID used as a cursor for pagination. For instance, if the last testimonial you fetched had an ID of `55`, adding `after=55` to the URL would fetch testimonials starting after the testimonial with ID `55`

For example, this would be a valid URL to request:
```
https://api.frontendexpert.io/api/fe/testimonials?limit=2&after=55
```

For Ref: https://www.algoexpert.io/frontend/coding-questions/infinite-scroll
  