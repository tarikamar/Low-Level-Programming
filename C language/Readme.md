# Project summary 🚀
Learning materials
   - **Jeff Szuhay - Learn C Programming: A beginner's guide to learning C programming the easy and disciplined way** 📖
   - [**Programiz C**](https://www.programiz.com/c-programming) 💻
   - **Wikipedia** 📑 


      
## Compiler ⚙️

                      ┌─────────────┐
                      │ SOURCE CODE │
                      │             │
                      └─────────────┘
                             │
                    ┌────────▼─────────┐
                    │                  │
                    │ 1.Preprocessor   │─────┐
                    │                  │     │      ┌──────────────┐
                    └──────────────────┘     └─────▶│ Expanded Code│
                                             ┌──────│              │
                    ┌──────────────────┐     │      └──────────────┘
                    │                  │     │
                    │ 2.Compiler       │◀────┘
                    │                  ├─────┐
                    └──────────────────┘     │      ┌──────────────┐
                                             └─────▶│ Assembly code│
                    ┌──────────────────┐     ┌──────│              │
                    │                  │◀────┘      └──────────────┘
                    │ 3.Assembler      │
                    │                  │─────┐
                    └──────────────────┘     │      ┌──────────────┐
                                             └─────▶│ Machine code │
                    ┌──────────────────┐     ┌──────│              │
                    │                  │     │      └──────────────┘
                    │ 4.Linker         │◀────┘
                    │                  │
                    └──────────────────┘
                             │
                             ▼
                      ┌─────────────┐
                      │ EXECUTABLE  │
                      │ CODE        │
                      └─────────────┘
