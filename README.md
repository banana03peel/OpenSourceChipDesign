# Open Source Chip Design Projects

Multiple chip designing projects strating from the basics.

List is as follows:
- Half Adder Designing.

## Steps Broadly to be followed.

This process is done using the [tt10-verilog-template]() from TinyTapeout.

### Fork the [tt10-verilog-template]() repository.
- Name the fork appropriate to the project.

### Go to source('src') folder from the fork.
 - From project folder open project.v file (verilog file).
 - Edit the project.v file and write your verilog code for your intended circuit.

### Go to 'Test' folder.
- Open 'tb.v' file (verilog).
- change given module name 'tt_um_example' to your fork name.
- In Makefile and ensure 'PROJECT_SOURCES' is assigned the 'project.v' file.
- Go to the 'test.py'(python) file and write your test becnch code.

### Go to 'docs' folder in the fork.
- In the 'info.md' file, write the specifications of your project for reference.

### Next up is the 'info.yaml' file.
- Change the title, author, discord, description, language with appropriate responses.
- Change 'top_module' to your maodule name'
- Ensure 'source_files' is 'project.v'.
- Add the name of your inputs and outputs.

### Go to the actions tab
- Run a workflow on docs, test, and gds.
- After the work flow ends, click on gds's finished workflow.
- Scroll down to get the 2d preview and 3D viewer of your chip.
