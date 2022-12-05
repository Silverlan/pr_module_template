# Pragma Module Template

This is a template repository for modules for the Pragma Game Engine. If you want to create your own custom binary module, you can click on the [**Use this template**](https://github.com/Silverlan/test_tmplr/generate) button above to do so.

Once the repository has been generated, you will have to edit the values in `template_pragma_module.json`:
* name: The name of the module as it will appear in the readme
* module_name: The internal name of the module (i.e. the name of the CMake target and the binaries). This name should always start with the prefix `pr_` and always be lowercase.
* install_directory: The directory where the module should be installed to, relative to the Pragma installation. This should be somewhere in `modules/`.

Once you have pushed the changes to this file, a GitHub workflow will be triggered, which will generate the final files (this may take a few minutes). This will also replace this readme with additional information and instructions.