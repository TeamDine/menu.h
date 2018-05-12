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

/*** Cabeceras locales ***/
/**
///Datos del profesor
#include "personaldata.h"       ///Información personal
#include "academyformation.h"   ///Formación academica
#include "academyproduction.h"  ///Documentos creados por el profesor
#include "teaching.h"           ///Clases impartidas
#include "tutorials.h"          ///Tutorias

**/
class Menu{
    private:
        ///Todas las clases
    public:
        void startMenu();                ///Interfas de menu
        void access();                   ///Menu entrada de datos del profesor
        void showData();                 ///Mostrar lista de codigos de profesores
};

#endif // MENU_H_INCLUDED
