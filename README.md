# Instaparse - Part 2: Photo Upload and Enhanced Filtering

**Instaparse (Part 2)** - extends the functionality of the original Instaparse app, allowing users to take photos directly within the app and upload them. Additionally, this update introduces a more complex filtering system for posts, ensuring that users can only view photos after posting their own. This part of the project demonstrates handling photo input from the camera and implementing business logic for user interactions and content filtering.

- Developer: Noah Russell
- Development Time: Approximately 1 hour
- Technologies Used: Swift, UIKit, Parse SDK (Back4App), Xcode

## Key Features

The following features have been successfully implemented in this phase:

- [✅] Photo Upload from Camera: Users can take photos directly within the app using the device’s camera, enhancing the user experience by allowing for spontaneous photo uploads.
- [✅] Manual Photo Upload for Simulator: Users testing on simulators (without access to a real camera) can manually add unique photos to the simulator’s Photos app to simulate the upload functionality.
- [✅] Post-Upload Visibility: Users are not able to view other users’ photos until they upload their own. This ensures that only after posting can users access the social feed.
- [✅] Time-Based Post Visibility: Users can only see photos posted by others after posting their own within the last 24 hours. This feature adds a time-based filtering mechanism to encourage real-time engagement.

## Optional Features

- [❌] No optional features have been implemented in this part.

## Future Enhancements

- [🔲] Post Interaction: Adding like and comment functionality to engage users further.
- [🔲] Photo Filters: Allowing users to apply filters or effects to the photos before posting.
- [🔲] User Notifications: Implementing push notifications to notify users when new photos are available.

## Video Walkthrough

Here’s a video walkthrough demonstrating the app’s core features:

<img style="max-width:300px;" src="lab_6/Lab3.gif" alt="Instaparse PT 2 Demo">
GIF created with VEED.io.

## Development Process

This phase of the project was focused on integrating camera functionality and implementing more complex post visibility logic. Here are some key highlights:

- Camera Integration: Added functionality to allow users to take photos directly from the app. The photos are then stored and displayed as part of the user's posts.
- Content Filtering: Introduced filtering logic to ensure that users can only see photos uploaded by others once they have contributed their own post within the last 24 hours.
- Backend Integration: Continued use of Back4App (Parse) for managing user data and storing photos.

## Challenges Faced

- Camera Permissions: Ensuring proper permission handling for accessing the device’s camera was straightforward but required proper configuration in the app’s settings.
- Simulator Limitations: Testing camera functionality on the simulator required using a workaround to manually add photos to the simulator’s Photos app.

## Key Takeaways

- Strengthened knowledge of integrating camera features into iOS apps.
- Gained experience in implementing time-sensitive filtering logic for content.
- Learned more about managing user-generated content with Back4App.

## Technologies Used

- Programming Language: Swift
- Frameworks: UIKit, Parse SDK (Back4App)
- Backend: Back4App (Parse Server)
- Development Environment: Xcode 14.0+
- Version Control: Git, GitHub

## License

Instaparse is licensed under the Apache License 2.0.
You may obtain a copy of the license at:
http://www.apache.org/licenses/LICENSE-2.0
