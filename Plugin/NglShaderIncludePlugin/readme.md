NglShaderIncludePlugin
====

プロジェクトルート/Plugin ディレクトリに配置することで, プロジェクトルート/Shaders ディレクトリをShaderIncludePathに自動追加するUE4プラグイン.
A UE4 plugin that automatically adds the project root/Shaders directory to the ShaderIncludePath by placing it in the project root/Plugin directory.

## Install
1. download and extract zip.
2. copy "NglShaderIncludePlugin" directory to "ProjectRoot/Plugins/".
3. enable NglShaderIncludePlugin in Plugin Editing Interface.

## Usage
1. make "Shaders" directory in project root.
2. make "youre_shader.ush" file in "Shaders" and define your functions.
3. input "/Project/youre_shader.ush" to "Include File Paths" in Custom Shader Node.
4. you can use functions of "youre_shader.ush" in Custom Shader Node.

## Licence
[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author
https://twitter.com/nagakagachi

