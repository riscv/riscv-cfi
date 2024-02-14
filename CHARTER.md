Advanced exploitation techniques based on code reuse, do not introduce new code in vulnerable
programs. Code reuse attacks are based on diverting the control flow of an application by overwriting
function pointers and return addresses. The Shadow Stack and Landing Pads task group will define
privileged and unprivileged ISA extensions that can be used by privileged and unprivileged programs
to protect the integrity of their control-flow. Specifically, for protecting backward-edges we will define
a shadow stack for storing return-addresses in each privilege level. For protecting forward-edges we will
design a flexible label based landing pads approach which will ensure that the execution adheres to the
application’s Control-Flow Graph. The design will follow the threat model compiled in CFI-SIG and will be
updated on demand.
