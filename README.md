**Prerequisites**

  * nodejs in PATH (apt-get install nodejs under ubuntu)

**How to get started**

`git clone https://github.com/Spielmeister/spellJS.git`

`cd spellJS`

`./git_update_submodules`

`cd spellCore && make && cd ..`

`cp spellCli/spellConfig.json.template spellCli/spellConfig.json`

`cd spellEd && ./start_dev_spelledserver $PATH_TO_YOUR_SPELL_WORKSPACE`


