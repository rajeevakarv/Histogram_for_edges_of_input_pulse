Project)#1:))
Design!and!implement!an!embedded,!stand0alone!68HCS12!program!that!will!display!a!histogram!of!
one0thousand,!rising!edge!pulse!inter0arrival!times.!The!inter0arrival!time!between!pulses!is!expected!to!
average!around!1.0!millisecond,!but!the!histogram!should!represent!the!range!of!100!“buckets”!
between!the!values!of!950!and!1050!microseconds.!Good!programming!practice!suggests!that!the!upper!
and!lower!limits!be!easily!configurable.!
!
When!your!program!is!invoked,!prompt!the!user!to!start!measurements.!After!the!user!enters!a!key,!
measure!the!required!1000!inter0arrival!times,!and!pause!for!user!input.!When!a!key!is!entered,!display!
one!line!of!text!indicating!the!inter0arrival!time!beginning!with!the!shortest!inter0arrival!time!observed(
in!the!range!of!interest,!followed!by!the!number!of!samples!at!that!value.!Do!not(display!lines!with!0!
counts.!Pause!the!program!after!each!line!(or!n!lines)!to!allow!examination!by!the!user,!and!continue!
with!the!next!key!entered.!!
!
• The!program!should!operate!in!an!infinite!loop!in!this!fashion!until!interrupted!or!killed!by!the!
user.!
• At!least!one!relevant!POST!routine!must!be!included!at!the!startup!of!your!program.!!
• The!suggested!implementation!language!is!C,!however,!assembly!language!may!be!used!in!
whole!or!part!if!desired.!
!
(This!program!will!be!used!in!subsequent!projects!as!a!tool!to!measure!the!software!jitter!of!a!
commercial!real0time!operating!system’s!attempt!to!generate!pulses!at!exactly!1.0!milliseconds.!It!will!
also!be!used!to!generate!pulses!that!produce!external!interrupts!to!the!“purple!box”!running!a!
commercial!operating!system,!which!will!measured!and!tabulating!the!interrupt!response!times.!HINT:!
design,!implement!and!comment!the!code!to!be!easily!modified!for!extension.)!
!
In!addition!to!the!demonstration!of!your!project,!a!brief!report!is!required!to!illustrate!your!design,!list!
the!trade0offs!and!assumptions!of!your!implementation!and!show!one!run!of!your!output.!Your!source!
code!should!be!included.!Your!project!and!deliverables!may!also!be!provided!in!electronic!format.!
