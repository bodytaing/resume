# Resume

A simple gh-pages resume.

#### Development Installation

- Fork this repository
- `brew update && brew upgrade ruby-build`
- `rbenv install 2.2.5`
- `bundle`
- Start your server: `middleman`
- Navigate to http://localhost:4567

To view all the components of this framework, navigate to http://localhost:4567/components

#### Building the Output

- `bundle exec rake build`

#### Publishing to GitHub Pages

- Publishing to `gh-pages` is done automatically by running `bundle exec rake publish`
- Visit http://your-github-username.github.io/resume/

#### Notes

Resume is built using a static generator: https://middlemanapp.com/
