# sublimeMQL4compile
MetaTrader4 (MQL4) compile for Sublime Text 3 

---

sublimeMQL4compile compiles [MQL4(MetaTrader4)](http://www.metaquotes.net/en/metatrader4/trading_terminal) by a [SublimeText 3](https://www.sublimetext.com/3). And an error log is indicated automatically.  

**[Screenshot]**

![sublimeMQL4compile](http://cdn-ak.f.st-hatena.com/images/fotolife/m/mofoolog/20160423/20160423130603.gif?1461384552 "sublimeMQL4compile-gif")

All files with which I deal by a MetaEditor (`.mq4` , `.mqh`) can be compiled.  It's also possible to compile the file which imported `.dll` and `.ex4`.  

&nbsp;

## Installation procedure

1. After whether it's installed in gitclorn downloads a zip file, a zip file is defrosted.

2. The place a sublimeMQL4compile folder establishes is in the `<Your>\<setting>\Sublime Text 3\Packages\` directory.

※ It doesn't correspond to Package Control for the moment.  

&nbsp;

## Setting

1. `sublimeMQL4compile.sublime-settings` filing in the `sublimeMQL4compile` directory is held.

2. A complete path of its `metaeditor.exe` is input to a `"compiler_path"` space.

Initialization is below.  

```json
{
    "compiler_path": "C:\\Program Files (x86)\\MetaTrader 4\\metaeditor.exe"
}
```

The PATH input when using Wine by Mac and Linux. (I'm not inspecting.)

```json
{
    "compiler_path": "/home/<Your Name>/.wine/drive_c/Program Files/MetaTrader 4/metaeditor.exe"
}
```

&nbsp;

## How to use

* **Shortcutkey : [ `Ctrl` + `4` ]**

or

* A Control Panel is opened. It's input to a Control Panel with `mql`. `MQL4 Compile` shown to a Control Panel is chosen and carried out.

&nbsp;

## Others

日本語のREADMEは[こちら](https://github.com/rchjp/sublimeMQL4compile/blob/master/README(ja).md)です。  

&nbsp;
