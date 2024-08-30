# Automated-Passenger-Boarding-Kiosk

## Overview
This project leverages Azure's AI services to automate and streamline the pre-flight boarding process. By using computer vision technology, the kiosk performs tasks such as identity verification, boarding pass recognition, emotion detection, and prohibited item detection, enhancing both security and efficiency at airports.

## Introduction
The traditional boarding process often involves time-consuming manual checks, which can create delays and inefficiencies. Introducing an automated passenger boarding kiosk addresses these issues by utilizing computer vision technology to streamline the process. This system not only enhances security by ensuring accurate passenger identification but also speeds up the boarding process, leading to a more efficient and seamless experience for passengers

## Requirements

#### Scan and Verify Passenger Information
- Capture and scan the passenger's ID card and boarding pass.
- Extract and cross-reference details between the boarding pass, ID card, and flight manifest.

#### Facial Recognition
- Record a 15-30 second video of the passenger.
- Use facial recognition to match the video with the ID card photo.

#### Prohibited Item Detection
- Scan carry-on baggage to detect prohibited items.
- Prevent boarding if any prohibited items are found.

#### Validation and Messaging
- Display a boarding confirmation if all validations are successful.
- Advise the passenger to see an airline representative if issues arise.

#### Simulated Kiosk Experience
- Create a manifest with 5+ passengers and generate corresponding digital IDs and boarding passes.
- Include a fabricated ID and video for facial recognition testing.
- Scan and flag prohibited items like lighters in carry-on baggage.
- Simulate the boarding process using Azure computer vision services.

#### Input Data Sources
- Flight manifest for 5 passengers.
- 5 digital ID cards and boarding passes.
- 15-30 second videos of each passenger’s face.
- Photos of each passenger's carry-on items.
