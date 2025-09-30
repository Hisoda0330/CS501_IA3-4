# CS501_IA3-4

A minimal Compose app showing:
- Top app bar with app title
- Bottom navigation (Home, Settings, Profile)
- Floating Action Button (FAB) that shows a Snackbar
- Proper `innerPadding` handling in `Scaffold` content

## Features
- **Top Bar**: `CenterAlignedTopAppBar` with title.
- **Bottom Nav**: `NavigationBar` with 3 items and selection state.
- **FAB + Snackbar**: FAB triggers `SnackbarHostState.showSnackbar`.
- **No Overlap**: `innerPadding` is applied to the content: `Modifier.padding(innerPadding)`.
