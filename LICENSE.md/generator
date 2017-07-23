// JavaScript Document

var normalb="abcdefghijklmnopqrstuvwxyz?+_-"
var changedb="двÇδзfбнijкlмиøрqяsтцvщxчz？＋＿－"


function changeText(_in, _out)
{
  var s="";
  var n=_in.value.toLowerCase();

  ///if (_in.value.length=="0") _arab.value="";
  
  for(i=0; i<n.length; i++)
  {
    var c=n.charAt(i);
    for(j=0; (j<normalb.length)&&(c!=normalb.charAt(j)); j++);
    if (j<normalb.length) { 
      s+=changedb.charAt(j);} else {
      s+=c;
    }
  }

  _out.value=s;

}

function focusFirst() {

  if (els = oTD.getElementsByTagName("input")) {
    els[0].focus();
  }
}

function highlight(field) {
field.focus();
  field.select();
}
