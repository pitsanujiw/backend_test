# Install
```
    $ git https://github.com/pitsanujiw/backend_test.git
    $ cd digitalHR-api
    $ npm install
```
# start project 
Beta Backend test ! 1.01

# Routes
```
    employmentCertifyLetter
        - GET /api/certifyLetter/employmentCertifyLetter/show
        - POST /api/certifyLetter/employmentCertifyLetter/add 
            [
                employeeID: string, 
                typeCertifyLetter: string, 
                firstName: string, 
                lastName: string, 
                note: string, 
                numberOfCopy: number
            ]

    certifyLetterForHousingLoan
        - GET /api/certifyLetter/certifyLetterForHousingLoan/show
        - POST localhost:3000/api/certifyLetter/certifyLetterForHousingLoan/add
            [
                employeeID: string, 
                typeCertifyLetter: string, 
                firstName: string, 
                lastName: string, 
                note: string, 
                numberOfCopy: number, 
                banks: { 
                    "BBL": number, 
                    "GHB": number,
                    "LHBank": number,
                    "UOB": number
                }
            ]
    
    certifyLetterForFurtherEducation
        - GET /api/certifyLetter/certifyLetterForFurtherEducation/show
        - POST /api/certifyLetter/certifyLetterForFurtherEducation/add
            [
                employeeID: string, 
                typeCertifyLetter: string, 
                firstName: string, 
                lastName: string, 
                note: string, 
                numberOfCopy: number
            ]


    GET /api/users/showAll
    GET /api/users/showOne
    POST /api/users/addOne [firstName, lastName, sex, email, image];
```

# Reference
```
    Word
    - https://github.com/Ziv-Barber/officegen
    Excel
    - https://github.com/natergj/excel4node
    PDF
    - http://pdfkit.org/
```