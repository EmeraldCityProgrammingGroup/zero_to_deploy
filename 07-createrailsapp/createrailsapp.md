<!SLIDE> 
# First, a Touch of Rails #

<!SLIDE command>
# Create the project
    $ mkdir rails_projects 
    $ cd rails_projects 
    $ rails new first_app
    
<!SLIDE>
File/Directory    Purpose
app/              Core application (app) code, including models, views, controllers, and helpers
config/           Application configuration
db/               Files to manipulate the database
doc/              Documentation for the application
lib/              Library modules
log/              Application log files
public/           Data accessible to the public (e.g., web browsers), such as images and cascading style sheets (CSS)
script/rails      A script provided by Rails for generating code, opening console sessions, or starting a local web server
test/             Application tests (made obsolete by the spec/)
tmp/              Temporary files
vendor/           Third-party code such as plugins and gems
README            A brief description of the application
Rakefile          Utility tasks available via the rake command
Gemfile           Gem requirements for this app
config.ru         A configuration file for Rack middleware
.gitignore        Patterns for files that should be ignored by Git
