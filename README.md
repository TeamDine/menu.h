# menu.h
///Cabecera de la clase Menu Principal

#ifndef MENU_H_INCLUDED
#define MENU_H_INCLUDED

/*** Cabeceras del sistema ***/
#include <iostream> ///Para cin/cout
#include <stdlib.h> ///Para los system()
#include <limits>   ///Para delimitar los cin
#include <string>   ///Para cadenas string
#include <string.h> ///Para cadenas char
#include <fstream>  ///Para archivos
#include <iomanip>  ///Para setw, right y left;
#include <stdio.h>  ///Para castear cadenas a enteros

/*** Cabeceras locales ***/
#include "professor.h"
#include "name.h"
#include "date.h"
#include "address.h"

class Menu{
    private:
        Professor teacher;      ///Objeto de tipo Profesor
    public:

        /***Interfas de Menu***/
        void startMenu();       ///Interfas de menu
        void access();          ///Menu entrada de datos del profesor
        void showData();        ///Mostrar lista de codigos de profesores
        void modifyData();
        void deleteData();
        void findData();

        /*** Metodos de Profesor ***/
        void insertPersonalData();          ///Ingresar datos personales
        void insertAcademicFormation();     ///Ingresar datos escolares
        void insertAcademicProduction();    ///Ingresar datos de publicaciones
        void insertTeachers();              ///Ingresar datos de las clases impartidas
        void insertTutorials();             ///Ingresar datos de alumnos tutorados
        

        /*** Metodos de tabla hash ***/
        void buildFile();
        void insertTable();
        void showTable();
        void 
};

#endif // MENU_H_INCLUDED

