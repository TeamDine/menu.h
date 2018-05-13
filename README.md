# menu.h
///Cabecera de la clase Menu Principal

#ifndef MENU_H_INCLUDED
#define MENU_H_INCLUDED

/*** Cabeceras del sistema ***/
#include <iostream>
#include <stdlib.h>
#include <limits>
#include <string>
#include <string.h>
#include <fstream>
#include <iomanip> ///Para setw, right y left;

/*** Cabeceras locales ***/
/**

#include "personaldata.h"
#include "academyformation.h"
#include "academyproduction.h"
#include "teaching.h"
#include "tutorials.h"

**/
class Menu{
    private:
        ///Todas las clases
    public:
        void startMenu();                ///Interfas de menu
        void access();      ///Menu entrada de datos del profesor
        void showData();                 ///Mostrar lista de codigos de profesores
};

#endif // MENU_H_INCLUDED
