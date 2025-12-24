# College Planner - University Data Repository

This repository contains course catalog data for universities used by the College Planner app.

## Structure

```
manifests/
  schools.json          # List of all available universities
profiles/
  [school_id].json      # Course catalog for each school
recipes/
  [format]_scraper.js   # Scraper scripts for different catalog formats
```

## Contributing

To add a new university:
1. Scrape the course catalog
2. Create a new profile JSON in `profiles/`
3. Update `manifests/schools.json`
4. Submit a Pull Request

## Data Format

See `university_profile_schema.json` in the main app repo for the complete schema.

## License

Course data © respective universities. This repository only hosts structured data for educational planning purposes.
