# lyroil Bot - Update History

This document tracks all significant updates and changes to the lyroil Discord bot.

## Version 1.2.0 (Current) - Leaderboard Enhancement Update

### New Features
- **Profile Pictures in Leaderboard**: Users' Discord avatars now appear next to their names in the leaderboard
- **Custom Background Images**: Server administrators can now set custom background images for their server's leaderboard
- **Interactive Navigation**: Added button controls for easier navigation through leaderboard pages
- **Visual Improvements**: Enhanced leaderboard design with better gradients, transparency, and readability

### New Commands
- **`setlbimage <image_url or attachment> [--delete]`**: Set or remove a custom background image for your server's leaderboard
  - Upload an image directly or provide a URL to set a custom background
  - Use `--delete` option to remove the custom background and revert to default
  - Requires `Manage Server` permission
- **`testbackground`**: Generates a clean, gradient background for your server's leaderboard
  - Creates a background with subtle decorative elements
  - No text overlay, just a visually appealing backdrop
  - Requires `Manage Server` permission

### Improvements
- **Enhanced Avatar Display**: User profile pictures appear with colored borders (special borders for top 3 ranks)
- **Better Readability**: Semi-transparent overlays ensure text is readable regardless of background image
- **Error Handling**: Improved error handling for image loading and file operations
- **Visual Hierarchy**: Better visual organization with alternating row colors and highlight effects

### Technical Improvements
- Added proper error handling for avatar loading
- Improved file system operations for background image storage
- Fixed path handling across different environments
- Added debugging and logging options for troubleshooting

## Version 1.1.0 - LastFM Enhancement Update

### New Features
- **LastFM Crown System**: Track who has listened to an album the most in a server
- **Enhanced Music Stats**: More detailed music listening statistics and visualizations
- **Artist Aliasing**: Create aliases for artists to improve tracking consistency

### Improvements
- Improved response time for LastFM commands
- Enhanced error handling for API rate limits
- Better data caching for frequently used information

## Version 1.0.0 - Initial Release

### Features
- Anime data commands
- LastFM integration
- Reputation system
- Server management tools
- Leveling system
- Utility commands

---

*For questions or suggestions about these updates, please join our support server.* 
