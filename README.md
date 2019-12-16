# reveal-template

Hosted at: https://ayushgarg0694.github.io/reveal-template/

#### Prerequisite

For development using yo template:
1. `npm install -g generator-reveal`
2. `npm install -g yo`
3. `brew install grunt`

yo is not required, you can add the markdown files manually (the actual file and in list.json).
it just helps with templating.

#### Development

1. Add new slide: `yo reveal:slide "Slide Title" --markdown`.
2. list.json handles ordering
3. run on a local server for testing: `grunt serve`
4. deploy to gh pages: `grunt deploy`
5. for more options refer: https://github.com/slara/generator-reveal