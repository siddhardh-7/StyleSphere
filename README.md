# UI Reference:
- https://www.figma.com/design/RxfRvaX0srgfAOBrGwlLIT/Brand-Store-Mobile-App-Design-(Community)?node-id=1-2&t=serqe6QzeKr4qGrW-0

# CodeBase Setup:
- https://medium.com/@ArashPro/how-to-structure-a-jetpack-compose-project-616b3fe22daa
- com.example.android
├── app
│   ├── android
│   └── host
│       
├── data
│   ├── network
│   │   ├── service
│   │   ├── client
│   │   ├── model
│   │   └── error
│   │
│   ├── db
│   │   ├── entity
│   │   ├── dao
│   │   ├── database
│   │   ├── converter
│   │   └── migration
│   │
│   ├── pref
│   │  
│   └── repository
│
├── domain
│   ├── model
│   └── repository
│
├── di
│   ├── modules
│   ├── scopes
│   └── components
│
├── presentation
│   ├── ui
│   │   ├──screen1 
│   │   │  ├── Screen1.kt
│   │   │  ├── VideModel1.kt
│   │   │  └── components
│   │   │      ├── Component1.kt
│   │   │      └── Component2.kt
│   │   │
│   │   └──screen2
│   │      ├── Screen2.kt
│   │      ├── VideModel2.kt
│   │      └── components
│   │          ├── Component1.kt
│   │          └── Component2.kt
│   │
│   ├── common
│   │   ├── shared components
│   │   └── shared viewmodels
│   │   
│   └── theme
│   │   ├── color
│   │   ├── shape
│   │   ├── theme
│   │   └── type
│   │
│   └── navigation
│       
├── notification
├── workers
└── utils
