# mbot-bluetooth-control-extension-blocks
mblock extension blocks for mbot bluetooth(serial) control more than convenient.

# file description
1. urimalsoft_mbot_blocks(folder): original source file.
2. urimalsoft_mbot_blocks.zip: for upload into mblock ide.

# todo and bug
1. (bug) "urimalsoft mbot program" block: include and define statement not working when sometimes. If you use this block, Check code converted with arduino c like below.
<code>#include <MeMCore.h></code>
<code>int _direction = 0;</code>
<code>int _speed = 100;</code>

 