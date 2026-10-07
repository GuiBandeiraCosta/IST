# IST

Course projects from my BSc (2019-2022) and MSc (2022-2024) in Computer Science and Engineering at Instituto Superior Técnico (IST), Lisbon.

Each course used to live in its own repository. They are gathered here by year, and each folder keeps its original commit history (`git log -- <folder>`). Several projects were group work; the course READMEs name the team members.

## 1st year (2019-2020)

| Folder | Course | Language | Project |
| --- | --- | --- | --- |
| [IAED](1st-Year-2019-2020/IAED) | Introdução aos Algoritmos e Estruturas de Dados (Introduction to Algorithms and Data Structures) | C | Weekly lab exercises and two projects: a logistics system for products and orders, and a database of friendly football matches built on hash tables and linked lists. |

## 2nd year (2020-2021)

| Folder | Course | Language | Project |
| --- | --- | --- | --- |
| [ASA](2nd-Year-2020-2021/ASA) | Análise e Síntese de Algoritmos (Analysis and Synthesis of Algorithms) | C++ | Two graph problems: the longest path and the minimum set of starting vertices in a DAG, and the cheapest split of processes between two processors, solved as a max-flow / min-cut (Edmonds-Karp). |
| [PO](2nd-Year-2020-2021/PO) | Programação com Objetos (Object-Oriented Programming) | Java | A store management application (products, clients, suppliers, orders and sales) built on the course's text-menu framework. |
| [SO](2nd-Year-2020-2021/SO) | Sistemas Operativos (Operating Systems) | C | TecnicoFS: a multithreaded file system with mutex and read-write lock strategies, later turned into a client-server system over Unix domain sockets. |

## 3rd year (2021-2022)

| Folder | Course | Language | Project |
| --- | --- | --- | --- |
| [BD](3rd-Year-2021-2022/BD) | Bases de Dados (Databases) | SQL, Python | A PostgreSQL database for a network of vending machines (schema, integrity constraints, queries, a sales view and OLAP analytics) with a small Flask web front end. |
| [CG](3rd-Year-2021-2022/CG) | Computação Gráfica (Computer Graphics) | JavaScript | Three Three.js scenes: an articulated object made of primitives, a spaceship orbiting a planet and collecting space debris, and lit origami figures with switchable materials and VR support. |
| [Comp](3rd-Year-2021-2022/Comp) | Compiladores (Compilers) | C++ | A compiler for the L22 language with Flex and Bison on the course's CDK library: scanner, parser, type checker, and XML and postfix (assembly) code generators. |
| [IA](3rd-Year-2021-2022/IA) | Inteligência Artificial (Artificial Intelligence) | Python | A Numbrix puzzle solver that models the puzzle as a search problem and solves it with A* search and a problem-specific heuristic. |
| [RC](3rd-Year-2021-2022/RC) | Redes de Computadores (Computer Networks) | C | A group messaging service: a directory server and a user client that talk over UDP (registration, login, groups) and TCP (posting and retrieving messages and files). |
| [SD](3rd-Year-2021-2022/SD) | Sistemas Distribuídos (Distributed Systems) | Java | Turmas: a replicated class-enrolment service with gRPC, a naming server, student, professor and admin clients, and gossip between replicas ordered by timestamps. |

## 4th year (2022-2023, first year of the MSc)

| Folder | Course | Language | Project |
| --- | --- | --- | --- |
| [PP](4th-Year-2022-2023/PP) | Procura e Planeamento (Search and Planning) | Python, MiniZinc | Multi-agent path finding (MAPF) as a constraint satisfaction problem: a Python script encodes the graph and agents and calls a MiniZinc model, increasing the time horizon until a plan is found. |

## Notes

- The larger test-case folders of IAED (`projectos/p1` and `projectos/p2`) are stored as `.zip` files to keep the repository small to clone. Unzip a file in place to restore its folder.
- Course-provided material (assignment statements, test suites and libraries such as CDK and po-uuilib) is kept alongside the code so the projects can still be built and tested.
