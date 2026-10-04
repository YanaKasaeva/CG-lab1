# Vulkan Starter App

## Лабораторная работа №1 по компьютерной графике

**Вариант 7 — тор.** Приложение на C++ и Vulkan отображает два процедурно
построенных тора. Интерфейс ImGui позволяет менять проекцию, положение,
поворот, масштаб и цвет объекта, а также параметры анимации. В корне проекта
находится отчёт `309_Касаева_Лаб1.docx`.

### Запуск на macOS

Требуются Vulkan SDK и CMake. Из корня проекта:

```bash
cmake --preset macos-debug
cmake --build build-macos-debug --parallel 1
./build-macos-debug/vulkan-starter-app
```
