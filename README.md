# Tour Agency Management System (C++)

A console-based tour agency management system developed as a team final project of the
Object-Oriented Programming course at IT STEP Academy (February–March 2024).

The application lets users browse and book hotels, tours and food services, manage their
purchases, and gives administrators a control panel for managing the agency's offer.
All data is saved to and loaded from text files.

## Features
- **Tours:** eight tour types (beach, gastro, hiking, safari, sightseeing, yacht,
  helicopter flight, multi-day tours) built on a common class hierarchy
- **Accommodation:** hotels with different room types and booking
- **Food services:** restaurants, cafés and canteens with menus
- **Users:** registration, login, purchases and the ability to cancel them
- **Admin panel:** managing the agency's data
- Custom exception classes for input and data validation
- File-based persistence (save/load)

## Technologies
C++, OOP (inheritance, polymorphism, virtual functions), STL, file I/O, exceptions,
Visual Studio, Git (team workflow)

## How to run
Open `OOP_Final_Project.sln` in Visual Studio and run the project (Ctrl+F5).
The application reads its data from the `data/` folder.

## Team
- **[Mishanja_Games](https://github.com/MishanjaGames)** — project architecture and
  `TourAgency` core, hotels, rooms and accommodation, map, hotel data save/load,
  hotel management menu
- **[pavlenkoMisha](https://github.com/pavlenkoMisha)** — food services: restaurants,
  cafés, canteens, dishes and related exceptions
- **[KundelyevaVika](https://github.com/KundelyevaVika)** — tours module (tour class
  hierarchy, tour container and exceptions), user accounts and data save/load,
  purchase cancellation, admin control panel, loading screen
