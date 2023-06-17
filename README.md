# LAMRS website

# Development

## Running the site locally

### OSX
Launch `Terminal.app` (located in Applications -> Utilities)

Navigate to your documents directory (or another place of your choosing)
`cd ~/Documents`

Verify you have `git` installed ([Install](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) git if needed)
`git --version`

Clone this code repository
`git clone git@github.com:smoil/lamrs.git`

Navigate to the project directory
`cd lamrs`

Verify bundler is installed `gem list bundler` (if not install bundler `gem install bundler`)

Run bundler to install gem dependencies `bundle`

Run the local jekyll server `bundle exec jekyll serve`

The site should be running locally. Start a web browser and open `http://127.0.0.1:4000/`
