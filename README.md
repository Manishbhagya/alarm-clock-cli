\# Alarm Clock CLI



A production-ready Python CLI alarm clock built with Typer and Rich.



\## Features



\* Create one-time alarms

\* Daily recurring alarms

\* Persistent JSON storage

\* Rich terminal interface

\* Background scheduler

\* Cross-platform audio notifications

\* Windows and Linux service installation

\* Timezone support

\* Structured logging

\* Automated testing



\## Technology Choices



\* Python 3.10+

\* Typer

\* Rich

\* Loguru

\* zoneinfo / tzdata



\## Architecture



```text

src/alarm\_clock/

├── cli.py

├── scheduler.py

├── storage.py

├── models.py

├── audio.py

├── service.py

├── timezone.py

├── tui.py

```



\### Key Components



\* \*\*CLI Layer\*\* – Typer-based command interface

\* \*\*Scheduler Engine\*\* – Alarm monitoring and triggering

\* \*\*Storage Layer\*\* – JSON persistence

\* \*\*Audio Layer\*\* – Cross-platform notifications

\* \*\*Service Layer\*\* – Windows/Linux service integration

\* \*\*Timezone Utilities\*\* – Timezone-aware scheduling



\## AI-Assisted Development Process



AI tools were used to:



\* Refine requirements

\* Explore architecture alternatives

\* Identify edge cases

\* Generate testing ideas

\* Review implementation decisions



Final engineering decisions, implementation review, debugging, validation, and testing were performed manually.



\## Testing



Run tests:



```bash

python -m pytest

```



Results:



\* 142 tests passed

\* 91.18% coverage



\## Example Usage



```bash

python -m alarm\_clock add 20:00 --label "Workout"



python -m alarm\_clock list



python -m alarm\_clock daemon

```



\## Design Decisions



\### Chosen



\* JSON persistence

\* Background scheduler thread

\* Rich terminal UI

\* Service support

\* Timezone support

\* Extensive automated testing



\### Avoided



\* Database dependency

\* Web UI

\* External backend services



The focus was reliability, maintainability, portability, and testability within the exercise scope.



