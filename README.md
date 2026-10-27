# TaskFlow

Offline-first task manager: Material 3, light/dark themes, priorities, filters,
swipe-to-delete with undo, progress bar, and local persistence.

## Run
```bash
cd taskflow
flutter create .      # generates android/ ios/ web/ etc. (one time)
flutter pub get
flutter run
```

## Structure
- `lib/models` – data classes
- `lib/services` – `TaskStore` (state + persistence) and `TaskScope`
- `lib/screens`, `lib/widgets` – UI
- `test/` – unit + widget tests (`flutter test`)
