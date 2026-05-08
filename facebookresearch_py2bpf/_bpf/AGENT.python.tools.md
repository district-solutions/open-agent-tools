# Agent Python Tools

- repo: facebookresearch/py2bpf
- repo_uri: https://github.com/facebookresearch/py2bpf

## File: facebookresearch_py2bpf/_bpf/_instructions.py

Prompts

```
['convert a list of BPF instruction objects and labels into a raw ctypes instruction array using convert_to_raw_instructions', 'create a Mov instruction to move data between registers, immediates, or memory operands in BPF programs', 'build an ALU64 arithmetic instruction like Add, Sub, Multiply, or Divide operating on registers or immediates', 'create a conditional jump instruction like JumpIfEqual or JumpIfGreaterThan comparing a register to an immediate or another register', 'create a Call instruction to invoke a BPF helper function by number or a Ret instruction to exit the program', 'open a perf event using perf_event_open with a PerfEventAttr structure and optional pid, cpu, group_fd, and flags', 'create a PerfEventAttr ctypes structure to configure perf event type, size, config, sample_period, and sample_type fields', 'create a PerfEventMmapPage ctypes structure to read perf event mmap page data including data_head, data_tail, and time fields', 'create a PerfEventHeader ctypes structure to parse perf event record headers with type, misc, and size fields', 'configure a SamplePeriodUnion ctypes union to set either sample_period or sample_freq for perf event sampling', 'run a raw Linux system call by number with arbitrary arguments via libc syscall', 'run a BPF system call with a command, attribute pointer, and attribute length', 'get a lazy-loaded ctypes handle to libc.so.6 for making low-level C calls', 'get the current thread errno value from libc __errno_location', 'review the _syscall module to understand BPF and raw syscall wrappers for eBPF programs', 'translate a list of VarInstructions into BPF instructions using the translate function', 'review the translate function that converts VarInstructions to BPF instruction lists with optional verbose output', 'review the opcode translator functions that handle JUMP_FORWARD, CALL_FUNCTION, COMPARE_OP, and other bytecode opcodes', 'review the pseudo-function call handlers for memcpy, addrof, ptr, deref, packet_copy, load_skb, and mem_eq', 'review the _mov, _lea, _memcpy, and _mov_const helper functions for BPF memory movement and address calculation']
```

Usage

```
{'convert_bpf_program_to_raw_instructions': 'convert a list of BPF instruction objects and labels into a raw ctypes instruction array using convert_to_raw_instructions', 'create_mov_instruction': 'create a Mov instruction to move data between registers, immediates, or memory operands in BPF programs', 'build_alu64_arithmetic_instruction': 'build an ALU64 arithmetic instruction like Add, Sub, Multiply, or Divide operating on registers or immediates', 'create_conditional_jump_instruction': 'create a conditional jump instruction like JumpIfEqual or JumpIfGreaterThan comparing a register to an immediate or another register', 'create_bpf_call_or_return_instruction': 'create a Call instruction to invoke a BPF helper function by number or a Ret instruction to exit the program'}
```

## File: facebookresearch_py2bpf/_bpf/_perf_event.py

Prompts

```
['convert a list of BPF instruction objects and labels into a raw ctypes instruction array using convert_to_raw_instructions', 'create a Mov instruction to move data between registers, immediates, or memory operands in BPF programs', 'build an ALU64 arithmetic instruction like Add, Sub, Multiply, or Divide operating on registers or immediates', 'create a conditional jump instruction like JumpIfEqual or JumpIfGreaterThan comparing a register to an immediate or another register', 'create a Call instruction to invoke a BPF helper function by number or a Ret instruction to exit the program', 'open a perf event using perf_event_open with a PerfEventAttr structure and optional pid, cpu, group_fd, and flags', 'create a PerfEventAttr ctypes structure to configure perf event type, size, config, sample_period, and sample_type fields', 'create a PerfEventMmapPage ctypes structure to read perf event mmap page data including data_head, data_tail, and time fields', 'create a PerfEventHeader ctypes structure to parse perf event record headers with type, misc, and size fields', 'configure a SamplePeriodUnion ctypes union to set either sample_period or sample_freq for perf event sampling', 'run a raw Linux system call by number with arbitrary arguments via libc syscall', 'run a BPF system call with a command, attribute pointer, and attribute length', 'get a lazy-loaded ctypes handle to libc.so.6 for making low-level C calls', 'get the current thread errno value from libc __errno_location', 'review the _syscall module to understand BPF and raw syscall wrappers for eBPF programs', 'translate a list of VarInstructions into BPF instructions using the translate function', 'review the translate function that converts VarInstructions to BPF instruction lists with optional verbose output', 'review the opcode translator functions that handle JUMP_FORWARD, CALL_FUNCTION, COMPARE_OP, and other bytecode opcodes', 'review the pseudo-function call handlers for memcpy, addrof, ptr, deref, packet_copy, load_skb, and mem_eq', 'review the _mov, _lea, _memcpy, and _mov_const helper functions for BPF memory movement and address calculation']
```

Usage

```
{'open_perf_event': 'open a perf event using perf_event_open with a PerfEventAttr structure and optional pid, cpu, group_fd, and flags', 'create_perf_event_attr': 'create a PerfEventAttr ctypes structure to configure perf event type, size, config, sample_period, and sample_type fields', 'create_perf_event_mmap_page': 'create a PerfEventMmapPage ctypes structure to read perf event mmap page data including data_head, data_tail, and time fields', 'create_perf_event_header': 'create a PerfEventHeader ctypes structure to parse perf event record headers with type, misc, and size fields', 'configure_sample_period_union': 'configure a SamplePeriodUnion ctypes union to set either sample_period or sample_freq for perf event sampling'}
```

## File: facebookresearch_py2bpf/_bpf/_syscall.py

Prompts

```
['convert a list of BPF instruction objects and labels into a raw ctypes instruction array using convert_to_raw_instructions', 'create a Mov instruction to move data between registers, immediates, or memory operands in BPF programs', 'build an ALU64 arithmetic instruction like Add, Sub, Multiply, or Divide operating on registers or immediates', 'create a conditional jump instruction like JumpIfEqual or JumpIfGreaterThan comparing a register to an immediate or another register', 'create a Call instruction to invoke a BPF helper function by number or a Ret instruction to exit the program', 'open a perf event using perf_event_open with a PerfEventAttr structure and optional pid, cpu, group_fd, and flags', 'create a PerfEventAttr ctypes structure to configure perf event type, size, config, sample_period, and sample_type fields', 'create a PerfEventMmapPage ctypes structure to read perf event mmap page data including data_head, data_tail, and time fields', 'create a PerfEventHeader ctypes structure to parse perf event record headers with type, misc, and size fields', 'configure a SamplePeriodUnion ctypes union to set either sample_period or sample_freq for perf event sampling', 'run a raw Linux system call by number with arbitrary arguments via libc syscall', 'run a BPF system call with a command, attribute pointer, and attribute length', 'get a lazy-loaded ctypes handle to libc.so.6 for making low-level C calls', 'get the current thread errno value from libc __errno_location', 'review the _syscall module to understand BPF and raw syscall wrappers for eBPF programs', 'translate a list of VarInstructions into BPF instructions using the translate function', 'review the translate function that converts VarInstructions to BPF instruction lists with optional verbose output', 'review the opcode translator functions that handle JUMP_FORWARD, CALL_FUNCTION, COMPARE_OP, and other bytecode opcodes', 'review the pseudo-function call handlers for memcpy, addrof, ptr, deref, packet_copy, load_skb, and mem_eq', 'review the _mov, _lea, _memcpy, and _mov_const helper functions for BPF memory movement and address calculation']
```

Usage

```
{'run_syscall': 'run a raw Linux system call by number with arbitrary arguments via libc syscall', 'run_bpf': 'run a BPF system call with a command, attribute pointer, and attribute length', 'get_libc': 'get a lazy-loaded ctypes handle to libc.so.6 for making low-level C calls', 'get_errno': 'get the current thread errno value from libc __errno_location', 'review_syscall_module': 'review the _syscall module to understand BPF and raw syscall wrappers for eBPF programs'}
```

## File: facebookresearch_py2bpf/_bpf/_template_jit.py

Prompts

```
['convert a list of BPF instruction objects and labels into a raw ctypes instruction array using convert_to_raw_instructions', 'create a Mov instruction to move data between registers, immediates, or memory operands in BPF programs', 'build an ALU64 arithmetic instruction like Add, Sub, Multiply, or Divide operating on registers or immediates', 'create a conditional jump instruction like JumpIfEqual or JumpIfGreaterThan comparing a register to an immediate or another register', 'create a Call instruction to invoke a BPF helper function by number or a Ret instruction to exit the program', 'open a perf event using perf_event_open with a PerfEventAttr structure and optional pid, cpu, group_fd, and flags', 'create a PerfEventAttr ctypes structure to configure perf event type, size, config, sample_period, and sample_type fields', 'create a PerfEventMmapPage ctypes structure to read perf event mmap page data including data_head, data_tail, and time fields', 'create a PerfEventHeader ctypes structure to parse perf event record headers with type, misc, and size fields', 'configure a SamplePeriodUnion ctypes union to set either sample_period or sample_freq for perf event sampling', 'run a raw Linux system call by number with arbitrary arguments via libc syscall', 'run a BPF system call with a command, attribute pointer, and attribute length', 'get a lazy-loaded ctypes handle to libc.so.6 for making low-level C calls', 'get the current thread errno value from libc __errno_location', 'review the _syscall module to understand BPF and raw syscall wrappers for eBPF programs', 'translate a list of VarInstructions into BPF instructions using the translate function', 'review the translate function that converts VarInstructions to BPF instruction lists with optional verbose output', 'review the opcode translator functions that handle JUMP_FORWARD, CALL_FUNCTION, COMPARE_OP, and other bytecode opcodes', 'review the pseudo-function call handlers for memcpy, addrof, ptr, deref, packet_copy, load_skb, and mem_eq', 'review the _mov, _lea, _memcpy, and _mov_const helper functions for BPF memory movement and address calculation']
```

Usage

```
{'translate_varinstructions_to_bpf': 'translate a list of VarInstructions into BPF instructions using the translate function', 'review_translate_function': 'review the translate function that converts VarInstructions to BPF instruction lists with optional verbose output', 'review_opcode_translators': 'review the opcode translator functions that handle JUMP_FORWARD, CALL_FUNCTION, COMPARE_OP, and other bytecode opcodes', 'review_pseudo_function_calls': 'review the pseudo-function call handlers for memcpy, addrof, ptr, deref, packet_copy, load_skb, and mem_eq', 'review_bpf_memory_operations': 'review the _mov, _lea, _memcpy, and _mov_const helper functions for BPF memory movement and address calculation'}
```

