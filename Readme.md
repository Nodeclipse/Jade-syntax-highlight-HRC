# This file is hrc for jade template syntax highlight in eclipse using colorer plugin (http://colorer.sourceforge.net/)

Version 0.0.1

## Usage:
  1. open and edit eclipsepath/plugins/net.sf.colorer_\*\.\*\.\*/colorer/hrc/proto\.hrc search for haml, and add below section below the haml section you just find.
        <prototype name="jade" group="inet" description="JADE">
            <location link="jade.hrc"/>
            <filename>/\.(jade)$/i</filename>
        </prototype>
  2. place this file(jade.hrc) into eclipsepath/plugins/net.sf.colorer_\*\.\*\.\*/colorer/hrc/
  3. open eclipse preferences, and under General-&gt;Editors-&gt;File Associations add *.jade to 'File types' add add editor 'Colorer XML Editor'
  4. change color theme in eclipsepath/plugins/net.sf.colorer_\*\.\*.\*/colorer/hrd/rgb to what you like
  
  Enjoy!!!

## History:
  0.0.1 initial checkin

## License
  Version: MPL 1.1/GPL 2.0/LGPL 2.1

