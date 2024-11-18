REMOTE RTV is a Windows-based media player that allows users to browse movie covers and play movies directly from the application. The app provides an interactive interface where clicking a movie cover plays the associated video, with movie names displayed as tooltips when hovering over the covers.

Features
Interactive Movie Covers: Display movie covers in a scrollable panel.
Play Movies: Click on a cover to play the corresponding movie using Windows Media Player.
Tooltips: Hover over movie covers to see the movie name.
Customization: Easily add your own movie covers, video files, and names by modifying the code.
Simple Setup: Straightforward setup process with instructions on how to get started.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/Redacted-Movie-Player.git
Open the solution in Visual Studio:

Open the .sln file located in C:\Users\yourusername\source\repos\Redacted Movie Player\Redacted Movie Player.sln.
Unblock Files:

Right-click on the solution file (.sln) and any blocked files (e.g., .exe, .dll, .mp4) > Properties > Unblock.
Update Movie Paths:

Modify the movieData array in the code to reflect the correct paths for your cover images, video files, and movie names:
csharp
Copy code
var movieData = new (string coverPath, string videoPath, string movieName)[]
{
    (@"C:\Path\To\CoverImage.jpg", @"C:\Path\To\VideoFile.mp4", "Movie Name"),
};
Build & Run:

After updating paths, build and run the project in Visual Studio.
Usage
Navigate: The movie covers will be displayed in a scrollable panel.
Play Movies: Click a cover to start playing the associated video.
Tooltips: Hover over a movie cover to see the movie name.
Terms of Service (TOS)
By using this software, you agree to the following terms:

Personal use only: Do not redistribute the application.
Liability: The developer is not responsible for any damages caused by this software.
Content Restrictions: No piracy or illegal content.
For further assistance, feel free to reach out on Discord: redactedjk.

Note I Do Not Provide The Moves Or Box Art you will need to get thems your self for more Help https://discord.gg/8fkJvX3Gs5
