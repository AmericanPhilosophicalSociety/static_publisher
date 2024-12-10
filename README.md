# static_publisher

## Serve site locally

bundle exec jekyll serve --config _config_development.yml

## Check for outdated gems

bundle outdated

## Documentation for user - fill this in

+ clone this site from git
+ download vscode and open site
+ install jekyll [or not? do we not want people to do this?]
+ jekyll serve command [or not?]
+ link to markdown guide, maybe a basic html explainer
+ how to change colors in sass
+ use yml file to configure navbar
+ how to find/upload appropriate images for use on the site

### Before deployment

+ comment google analytics back in
+ delete unused files from includes/img. maybe provide a list of what can be deleted and what should not be deleted (don't delete favicon etc)

### Troubleshooting

+ check for inaccurate spacing, commas, line breaks in yml files
+ for authors, check for exact match in name spelling
+ for image files, check name and file extension are spelled correctly, file is located in correct directory
+ vscode will show errors in html sometimes, doesn't work for liquid
+ check html and liquid tags opened and closed properly