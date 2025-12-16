# System Overview

The dataproc-agent processes structured input files containing a header
and a sequence of records. The header specifies metadata such as
record_count, while records contain payloads processed in FAST_MODE
or normal mode.

The system assumes well-formed inputs and relies on header values
to guide record parsing and processing.
