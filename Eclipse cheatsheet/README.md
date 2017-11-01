## Useful Eclipse settings
There are some useful tricks that can make using Eclipse easier.  
- For Git users, enable file tracing from other location <br />
Say I have an Eclipse project, and I want to know whether a file is edited from other editors/IDEs or not...

  `Windows > Preferences > General > Workspace`

  Enable checkboxes __Refresh using native hooks and polling__ and __Refresh on access__

- Replace tabs with white spaces

  `Windows > Preferences > General > Editors > Text Editors`

  Change the number of spaces for a tab by modifying __Displayed tab width__;

  Enable checkbox __Insert spaces for tabs__

  - _XML_ files
  
    `Windows > Preferences > XML > XML Files > Editor`

    Select __Indent using spaces__ and set __Indentation size__

- Auto-indent

  `Windows > Preferences > Java > Code Style > Formatter`

  Click __Edit__ to open the current formatter profile; The __Indent__ section lists several options for auto-indent

- Show warnings for Javadoc errors

  `Windows > Preferences > Java > Complier > Javadoc`

  - check __Process Javadoc comments__
  - set __Malformed Javadoc comments__ to _Warning_
    - set __Only consider members as visible as__ to _Private_
    - check __Validate tag arguments__
  - set __Missing Javadoc tags__ to _Ignore_
  - set __Missing Javadoc comments__ to _Ignore_

- Show warnings for Java potential warnings/problems

  `Windows > Preferences > Java > Complier > Errors/Warnings`

  - set __Potential null pointer access__ to _Warning_
  - set __Value of method parameters is not used__ to _Warning_

- Change file encoding to `UTF-8`

  `Window > Preferences > General > Workspace`

  Under __Text file encoding__ section, set to _Other_ and _UTF-8_

- Set a visible indicator for long text margins

  `Windows > Preferences > General > Editors > Text Editors`

  set checkbox __Show print margin__ and set the print margin column

- Auto-fix imports when saving

  `Windows > Preferences > Java > Editors > Text Editors`

  Check __Organize imports__

- Automatically groups static imports

  `Windows > Preferences > Java > Code Style > Organize Imports`

  Click __New Static...__ and enter _*_ to group all the static imports together

-
