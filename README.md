# 📚 Bookshelf System (Estante de Livros)

A Java desktop application designed to manage a personal book collection, supporting operations such as adding, searching, updating reading statuses, and filtering books by various attributes.

Developed as an academic project for the Object-Oriented Programming (OOP) coursework at UFPB.

---

## 🚀 Features

- **Book Management:** Register new books and remove existing ones.
- **Reading Status Tracking:** Monitor and update status (e.g., *Lido*, *Lendo*, *Não lido*).
- **Advanced Filtering:**
  - Search by Author
  - Search by Title
  - Search by Genre
  - Search by Reading Status
- **Custom Exception Handling:** Dedicated exceptions for missing authors, titles, and genres.
- **Interactive UI:** Simple desktop interface using Java `JOptionPane`.

---

## 🛠️ Tech Stack & Architecture

- **Language:** Java 8+
- **Paradigm:** Object-Oriented Programming (Polymorphism, Interfaces, Encapsulation, Custom Exceptions)
- **GUI:** Java Swing (`JOptionPane`)

### Project Structure
```text
br.ufpb.estante.projeto/
├── Estante.java                      # Core interface defining operations
├── EstanteList.java                  # List-based implementation of Estante
├── Livro.java                        # Model representing a book entity
├── ProgramaEstantedeLivros.java       # Main class with GUI interaction
├── AutorInexistenteException.java    # Custom exception for missing authors
├── GeneroInexistenteException.java   # Custom exception for missing genres
└── TituloInexistenteException.java   # Custom exception for missing titles
