# AAAconv: Gestión de convenios (Laravel)

Aplicación web en **Laravel 12** con **Livewire** (starter kit oficial) y autenticación incluida. Sobre esa base se modeló la gestión de convenios entre entidades y facultades.

## Modelo de datos
Migraciones y modelos para: `Facultad`, `Carrera`, `Entidad`, `Convenio`, `ConvenioFacultad` (relación convenio-facultad) y `DocumentoConvenio` (documentos adjuntos).

## Stack
PHP 8.2+ · Laravel 12 · Livewire + Flux + Volt · Pest · Pint

## Cómo correrlo
```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm install && npm run dev
php artisan serve
```

## Estado
Base del proyecto: autenticación, estructura de base de datos y vistas del starter kit. Las pantallas de convenios están pendientes.

## Autor
Gianluck Pastor, estudiante de Ingeniería de Sistemas (UPeU).
