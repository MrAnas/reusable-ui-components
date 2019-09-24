https://img.shields.io/static/v1?label=ELM&message=UI/UX&color=blueviolet

# UI/UX Reusable Components

## How to use The Reusable Components


### Dependences:
-	Bootstrap

### Supported External Libraries:
-	Primeng

Available Components:
-	Pagination (Primeng)
-	Accordion (Primeng)


### import the library:
-	Importing full library
```@import '~node_modules/npmcssanas/assets/scss/components/elmUI;```

-	Importing Primeng Library

```@import '~node_modules/npmcssanas/assets/scss/components/primeng/all;```

-	Importing without Primeng Library
```@import '~node_modules/npmcssanas/assets/scss/components/elmUIdefault;```

-	


### Using The components:

### Accordion:
``npm install primeng``

#### Importing

```import {AccordionModule} from 'primeng/accordion';```

#### Getting Started
Accordion element consists of one or more p-accordionTab elements. Title of the tab is defined using header attribute.

```
<p-accordion>
    <p-accordionTab header="Header 1">
       Content 1
    </p-accordionTab>
    <p-accordionTab header="Header 2">
        Content 2
    </p-accordionTab>
    <p-accordionTab header="Header 3">
        Content 3    
    </p-accordionTab>
</p-accordion>
```


To only Import in your accordion to your styles.scss:
```@import '~node_modules/npmcssanas/assets/scss/components/priming/accordion;```


### Pagination:
```npm install primeng```

#### Import

```import {PaginatorModule} from 'primeng/paginator';```

#### Getting Started
Paginator is defined using p-paginator element.

```<p-paginator></p-paginator>```

#### Rows and TotalRecords
Rows and TotalRecords define how many pages the paginator should display. Paginator below will have 10 pages.

```<p-paginator [rows]="10" [totalRecords]="100"></p-paginator>```

To only Import in your accordion to your styles.scss:
```@import '~node_modules/npmcssanas/assets/scss/components/priming/pagintation;```



	

### Upcoming:
-	Fileupload
-	CSS Grid
-	Wizard
