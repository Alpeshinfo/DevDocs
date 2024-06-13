
## What is YAML

YAML (YAML Ain't Markup Language) is a human-readable data serialization standard that is commonly used for configuration files and data exchange between languages with different data structures. It is designed to be easy to read and write and is often used in applications where data readability is crucial.

#### Key Features of YAML
   **Human-readable**: The syntax is designed to be easy for humans to read and write.
   **Hierarchical:** YAML supports complex data structures, including nested maps (dictionaries) and lists (arrays).
   **Portable:** It is language-agnostic and can be used across different programming environments.
   **Flexible:** YAML can handle a wide variety of data types, including scalars (strings, numbers, booleans), lists, and dictionaries.

#### Basic Syntax
   **Indentation / Scalars / Key-Value Pair :** 
   <sub>YAML uses indentation to represent structure. Indentation is done with spaces (not tabs).<br>Key-value pairs are used to represent data. A colon and space (: ) separate keys from values.</sub>
   ```
   string: "Hello, YAML"
   integer: 42
   float: 3.14
   boolean: true
   null_value: null
   ```
   **Sequences (Lists):** 
   <sub> Sequences represent ordered collections of items. Each item in the list is prefixed with a dash (-).</sub>
   ```
   Company ABC:
      - SERVER 01
      - SERVER 02
      - SERVER 03
      - SERVER 04
   Company XYZ
      - SERVER A1
      - SEVERR A2
      - SEVERR A3
      - SEVERR A4
   ```
   **List of objects (Nested):**
   <sub>YAML allows for nested mappings and sequences, providing a way to represent complex data hierarchies.</sub>
```
company:
  name: Example Corp
  departments:
    - name: Engineering
      head: Alice Smith
      employees:
        - name: Bob
        - role: Developer
        - name: Carol
        - role: QA
    - name: Marketing
      head: Dave Johnson
      employees:
        - name: Eve
        - role: Manager
        - name: Frank
        - role: Analyst
```
**Inline Notation**
<sub>YAML supports a more compact inline notation for both mappings and sequences.</sub>
```
inline_sequence: [Red, Green, Blue]
inline_mapping: {key1: value1, key2: value2}
```

**Multi-line Strings**
<sub> Multi-line strings can be represented using the pipe (|) or greater-than (>) symbols.
| preserves newlines within the string. > folds newlines into spaces.<sub>
```
literal_block: |
  This is a multi-line string.
  Newlines are preserved.
```
```
folded_block: >
  This is a multi-line string.
  Newlines are folded into spaces.
```  

**7. Comments**
<sub>Comments in YAML start with a hash (#) and extend to the end of the line.</sub>

```
# This is a comment
key: value  # This is an inline comment
```
**8. Aliases and Anchors**
<sub>YAML supports anchors (&) and aliases (*) to reuse data structures.<sub>

```
defaults: &defaults
  adapter: postgres
  host: localhost

development:
  database: dev_db
  <<: *defaults

test:
  database: test_db
  <<: *defaults
```
**9. Tags and Types**
<sub>YAML allows explicit typing using tags (!). This is more advanced and typically used when specific data types need to be enforced.</sub>
```
integer: !!int 42
string: !!str "Hello"
float: !!float 3.14
```
