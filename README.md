too-many-items.js
=================

function procCmd(cmd){  var cmd = cmd.split(" ");  if(cmd[0] == "give"){  addItemInventory(parseInt(cmd[1]), parseInt(cmd[2]));  }  }
