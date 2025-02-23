# **Aurora**  
Aurora is a smart flashcard app that uses AI to generate flashcards from documents, helping you study efficiently.

## 📌 Features  
- Create, edit, and organize flashcard decks.  
- Generate flashcards automatically from PDFs or pasted text.  
- Review cards using the SM-2 spaced repetition algorithm.  
- Practice with multiple-choice and manual input modes.  
- Light and dark themes for better readability.  

## 📸 Screenshots  
_(Add screenshots here)_  

## 📦 Packages & Technologies  

| Description             | Package              |  
|-------------------------|----------------------|  
| Architecture           | Bloc Pattern         |  
| State Management       | flutter_bloc         |  
| Dependency Injection   | get_it               |  
| Theming               | flex_color_scheme    |  
| OCR (Text Recognition) | google_ml_vision     |  
| Database              | Isar                 |  

## 🩻 Project Structure  
```
lib  
│  
│_ 📁src  
   │  
   │__ 📁core  
   │   │__ 📁errors <- Define errors and exceptions  
   │   │__ 📁router <- Generated router & route names  
   │   │__ 📁services <- Dependency injection & internet connection  
   │   │__ 📁theme <- Define themes & dynamic theming  
   │   │__ 📁utils <- Constants (enums, strings, etc.)  
   │   │__ 📁widgets <- Shared widgets used in multiple screens  
   │  
   │__ 📁features  
      │  
      │__ 📁cards  
         │__ 📁controller <- Bloc for state management  
         │__ 📁data <- Data retrieval and caching  
         │   │__ 📁models <- Business logic models  
         │   │__ 📁data_source <- Works with database and API  
         │   │__ 📁repository <- Combines and maps data  
         │__ 📁presentation <- Screens and widgets  
```

## 🏃‍♂️ Install & Run The App  
1. Clone the project:  
   ```
   git clone https://github.com/your-repo/aurora.git
   ```  
2. Navigate to the project directory and run:  
   ```
   flutter pub get
   ```  
3. (If using an API) Create a `.env` file and add necessary API keys.  
4. Run the app:  
   ```
   flutter run
   ```

## 💡 Contribution  
Feel free to contribute by adding features, reporting bugs, or making a pull request.

## 🗺️ Roadmap  
✅ Implement spaced repetition (SM-2).  
⏳ Improve AI flashcard generation.  
✅ Add multiple-choice practice mode.  
⏳ Enhance UI/UX with animations.  

## 🗞️ License  
MIT License (Ensure to remove author credits and API keys if applicable).  
