# Python Network and Utility Modules

## Module 1: TCPNetLib

### Hex Code:
`A001`

### Suggested Module Names:
- NetLibTCP
- PyTCPNet
- TCPNetworkLib
- TCPCommLib

### Module Description:
The TCPNetLib module is a Python library designed to facilitate TCP-based network communication. It provides a robust framework for creating TCP clients and servers, handling connections, and transferring data between networked systems. The module abstracts the complexities of TCP socket programming, offering easy-to-use functions for sending and receiving messages, managing connections, and handling network errors. TCPNetLib is ideal for developers building networked applications, enabling reliable and efficient communication over TCP.

---

## Module 2: STUNClient

### Hex Code:
`A002`

### Suggested Module Names:
- PySTUN
- STUNNet
- NATTraversal
- STUNTools

### Module Description:
The STUNClient module is a Python tool that implements the STUN (Session Traversal Utilities for NAT) protocol. This module allows developers to discover their public IP address, determine the type of NAT they are behind, and assess if peer-to-peer connections are possible. STUNClient is essential for applications requiring NAT traversal, enabling direct communication between devices across different network environments. The module provides a simple interface for querying STUN servers and interpreting their responses, making it easier to establish connections in challenging network conditions.

---

## Module 3: ShadowsocksProxy

### Hex Code:
`A003`

### Suggested Module Names:
- ShadowProxy
- PyShadowsocks
- ProxySocks
- SecureProxy

### Module Description:
The ShadowsocksProxy module is a Python implementation of the Shadowsocks protocol, a secure proxy designed to protect privacy and bypass internet censorship. This module allows users to create and manage Shadowsocks servers and clients, enabling secure and encrypted communication over the internet. With features for traffic obfuscation, encryption, and multi-user support, ShadowsocksProxy is an ideal solution for users who need to ensure privacy and security in their online activities. The module is designed for ease of use, with straightforward configuration options and support for various encryption methods.

---

## Module 4: GateForward

### Hex Code:
`A004`

### Suggested Module Names:
- PortForwarder
- NetGate
- PyForward
- GatewayRouter

### Module Description:
The GateForward module is a Python tool for network port forwarding and gateway management. This module allows users to set up port forwarding rules, route traffic between different network interfaces, and manage gateways in a networked environment. GateForward is ideal for developers and network administrators who need to control traffic flow within their networks, enabling more efficient management of network resources. The module supports a variety of protocols and provides an easy-to-use interface for configuring and managing forwarding rules.

---

## Module 5: FastTaskLaunch

### Hex Code:
`A005`

### Suggested Module Names:
- TrayServer
- QuickServeIcon
- WebTrayLauncher
- TaskbarFastAPI

### Module Description:
The FastTaskLaunch module is designed to streamline local development by integrating a FastAPI server with a taskbar icon for quick access. This module creates a taskbar icon that allows users to start a local FastAPI server with a single click. Once the server is running, users can easily open their default web browser to the local server's URL by clicking a button on the taskbar icon. The module is ideal for developers who frequently start and stop local servers during development and want a more efficient way to manage these tasks without relying on command-line operations.

---

## Module 6: WinTrack

### Hex Code:
`A006`

### Suggested Module Names:
- WindowSpy
- MultiOSWindow
- ActiveWinScanner
- OSWindowLister

### Module Description:
The WinTrack module is a cross-platform solution designed to retrieve the titles of active and open windows on a user's desktop. This module provides a simple interface for developers and system administrators to monitor window activity across different operating systems, including Windows, macOS, and Linux. WinTrack can identify the currently active window title and list all open window titles on the system, making it useful for automating tasks, tracking user activity, or integrating with other desktop applications. The module leverages platform-specific libraries and command-line tools to ensure compatibility and performance across multiple environments.

---

## Module 7: ScreenSnap

### Hex Code:
`A007`

### Suggested Module Names:
- SnapShotter
- PyScreenCap
- AutoScreenSave
- ScreenCapturePro

### Module Description:
The ScreenSnap module is a lightweight and versatile tool for capturing screenshots and saving them automatically to a designated folder. Whether you're monitoring a process, creating a time-lapse of your desktop activity, or simply saving snapshots for documentation, ScreenSnap provides an easy-to-use solution. The module generates timestamped filenames for each screenshot, ensuring that no two screenshots are overwritten. With support for different operating systems, ScreenSnap is an ideal utility for developers, content creators, and anyone who needs to automate the process of screen capturing.

---

## Module 8: KeyMouseTracker

### Hex Code:
`A008`

### Suggested Module Names:
- InputMonitor
- PyInputLogger
- ActivityCapture
- MouseKeyMonitor

### Module Description:
The InputMonitor module is a simple yet powerful tool for capturing and logging mouse and keyboard activity on your system. Leveraging the pynput library, this module tracks every mouse click and key press, providing real-time feedback on user interactions. Ideal for use cases such as user behavior analysis, input logging, or developing automated testing scripts, InputMonitor offers a straightforward interface to monitor and record input events across different operating systems. Whether you're a developer looking to track input for debugging or a researcher analyzing user activity, InputMonitor delivers the functionality you need in an easy-to-use package.

---

## Module 9: MouseMover

### Hex Code:
`A009`

### Suggested Module Names:
- ClickAutomate
- PyMouseControl
- AutoClicker
- MouseMotion

### Module Description:
The MouseMover module is a Python utility designed to automate mouse movements and clicks on your system. With simple functions to move the mouse to specific coordinates and perform single or multiple clicks, this module is ideal for tasks such as GUI automation, repetitive task automation, and automated testing. MouseMover leverages the pynput library to provide a seamless and cross-platform solution, making it easy to script and automate mouse interactions with minimal effort. Whether you're a developer looking to streamline workflows or a tester needing to simulate user input, MouseMover delivers precise and reliable mouse control.

---

## Module 10: PySourceInspect

### Hex Code:
`A010`

### Suggested Module Names:
- PySourceInspect
- CodeReflector
- SourceAnalyzer
- PyCodeScanner
- InspectoPy

### Module Description:
The PySourceInspect module is a comprehensive tool for analyzing Python source code within a given folder. Scanning all .py files provides detailed insights into the structure of the code, including lists of modules, classes, and functions defined in each file. Additionally, it tracks the usage of functions, global variables, and class attributes across the codebase. The results are saved as JSON, allowing for easy review and further processing. This module is particularly useful for code auditing, documentation generation, and understanding large or unfamiliar codebases.

---

## Module 11: ImageThrift

**Hex Code:** 
`A011`

### Suggested Module Names:
- ImageThrift
- S3ThriftCache
- ThriftImageHandler
- ImageThriftServer

### Module Description:
The ThriftImageService module is a comprehensive solution designed to handle image retrieval and processing via a Thrift-based service. The module interfaces with S3 to fetch images by path or UUID, compute hashes, retrieve vectors, and manage caching for improved performance. It exposes a set of APIs through a Thrift server, allowing for easy interaction with Thrift clients. The server efficiently processes requests, caches results locally, and provides benchmark capabilities to evaluate performance. This module is ideal for scalable applications that require fast and reliable image processing and retrieval services.

---

## Module 12: UDPHolePunch

**Hex Code:** 
`A012`

### Suggested Module Names:
- PunchTest
- UDPHolePuncher
- NATHolePunch
- UDPConnect

### Module Description:
The UDPHolePunch module is a Python-based tool for testing UDP connectivity and NAT traversal techniques. It includes a basic UDP server and client setup, along with methods to attempt UDP hole punching—a technique used to establish direct communication between peers in a NAT environment. The module is designed to help developers and network engineers test and understand the feasibility of direct peer-to-peer connections in various network configurations. With features for both server-client communication and peer-to-peer connection testing, UDPHolePunch is an essential tool for exploring NAT traversal strategies.

---

## Module 13: ECCrypto

**Hex Code:** 
`A013`

### Suggested Module Names:
- Secp256k1Tools
- ECCSigner
- Secp256k1Utils

### Module Description:
The ECCSECP256K1 module provides essential cryptographic operations using Elliptic Curve Cryptography with the SECP256k1 curve. This module allows for the generation of private and public keys, hashing of public keys using SHA-256, signing of the hash, and verification of signatures. By utilizing the ecdsa library, this module offers a straightforward interface for secure key management and digital signature operations. It is ideal for applications requiring robust cryptographic functionality, such as blockchain technologies, secure communications, and authentication systems.

---

## Module 14: DiscScanner

**Hex Code:** 
`A014`

### Suggested Module Names:
- DiskInspector
- DiscWriter
- MountPointChecker
- DiskUtil

### Module Description:
The DiscScanner module is a Python tool designed for disk inspection and management. It scans all available disks, identifies their mount points, and checks if the root folder is writable by the current user. The module includes functionality to write a JSON file containing a unique disk ID and UUID to the root of writable disks. This module is useful for disk management tasks, system administration, and automating disk-related processes, ensuring that disks are properly identified and configured with essential metadata.

---

## Module 15: EventTracker

**Hex Code:** 
`A015`

### Suggested Module Names:
- EventLogger
- EventSerializer
- EventManager
- SystemEvents

### Module Description:
The EventTracker module is a Python library designed for handling and managing computer events. It supports various event types, including new disk ID assignments, disk connections and disconnections, service shutdowns, and connection starts and ends. The module utilizes data classes with statically typed fields to define events and provides methods for serializing events to JSON and deserializing JSON back into event objects. This module is ideal for systems that need to track and log various system events, enabling efficient storage and retrieval of event data.

---

## Module 16: ScrapeMaster

**Hex Code:** 
`A016`

### Suggested Module Names:
- DataExtractor
- ScraperSuite
- WebHarvest
- InfoScraper

### Module Description:
The ScrapeMaster module is a Python library for scraping data from various platforms and sources. It includes specialized classes for extracting information from YouTube, Pinterest, research papers, Telegram, Twitter, and general websites. Each class is tailored to handle the specific structure of the respective platform's pages, providing a consistent interface for scraping and processing data. The module supports extensibility, allowing for additional scrapers to be implemented as needed. It is ideal for data collection tasks, enabling users to efficiently gather and organize information from multiple online sources.

---

## Module 17: ServiceRegistry

**Hex Code:** 
`A017`

### Suggested Module Names:
- ServiceManager
- ServiceDiscovery
- ServiceHub
- ServiceTracker

### Module Description:
The ServiceRegistry module provides a FastAPI-based service registry and recovery system. It enables clients to register and manage various types of services, computers, connections, transports, and routes in a distributed network. With endpoints for service registration, listing known entities, and handling connections and transports, this module supports dynamic service discovery and management. It is designed for environments where service availability, connection management, and transport handling are crucial, offering a centralized way to track and interact with services in a networked system.

---

## Module 18: SurveyService

**Hex Code:** 
`A018`

### Suggested Module Names:
- PySurvey
- PollService
- SurveyManager
- FeedbackCollector

### Module Description:
The SurveyService module is a Python-based framework designed for creating, managing, and collecting responses from surveys. This module allows users to design customizable surveys with various question types such as multiple choice, text input, ratings, and more. SurveyService offers an intuitive interface for distributing surveys to participants and collecting their responses in real time. The collected data can be exported in various formats, making it easy to analyze and report on survey results.

SurveyService is ideal for researchers, businesses, and organizations looking to gather feedback, conduct polls, or perform market research. The module supports integration with web applications through a RESTful API, enabling seamless embedding of surveys within websites or mobile apps. Additionally, it includes features like response validation, anonymous submissions, and result visualization to enhance the survey-taking experience.

---

## Module 19: ModelDownloader

**Hex Code:** 
`A019`

### Suggested Module Names:
- HuggingFaceModelManager
- ModelFetch
- PyModelDownloader
- HuggingFaceLoader

### Module Description:
The ModelDownloader module is a Python tool designed to streamline the process of downloading machine-learning models from Hugging Face. This module automatically creates a folder named "Models" and organizes the downloaded model files into a subfolder named after the model, such as "Gemini 2B Pocket Tiger."

After downloading the model files, ModelDownloader computes a cryptographic hash for each file using the Blake2b hashing algorithm, ensuring data integrity and security. The module then generates a metadata file that includes the following details:
- The name of the model's folder.
- A list of all downloaded files along with their respective paths.
- The size of each file.
- The Blake2b hash of each file.

This metadata file provides a comprehensive summary of the downloaded model, making it easy to verify file integrity and manage multiple models. The ModelDownloader is ideal for machine learning practitioners, researchers, and developers who frequently work with Hugging Face models, providing a convenient and secure way to manage model files.

## Coding Pattern

- The code for each module follows a hex pattern.
- The code length is a minimum of 4 digits.
- For each new code, the last module code is incremented by 1.
  - Example: If the last module code was A187, the next module code will be A188.
  - If the last module code is A999, the next module code will be B001.

### Current Modules and Their Codes

| Module Name         | Code |
| ------------------- | ---- |
| TCP Netlib          | A001 |
| STUNClient          | A002 |
| Shadowsocksproxy    | A003 |
| GateForward         | A004 |
| FastTaskLaunch      | A005 |
| WinTrack            | A006 |
| ScreenSnap          | A007 |
| KeyMouseTracker     | A008 |
| MouseOver           | A009 |
| PySourceInspect     | A010 |
| ImageThrift         | A011 |
| UDPHolePunch        | A012 |
| ECCrypto            | A013 |
| DiscScanner         | A014 |
| EventTracker        | A015 |
| ScrapeMaster        | A016 |
| ServiceRegistry     | A017 |
| SurveyService       | A018 |
| ModelDownloader     | A019 |


# SearchResult

This Python code snippet involves the use of the `pydantic` library for creating a data model called `SearchResult`. Below is a detailed breakdown of the code:

## 1. Importing Important Libraries

- **BaseModel, Field, and HttpUrl**: Imported from `pydantic`, these are used for creating and validating the data model.
- **datetime**: Used to work with date and time.
- **numpy**: Imported as `np`, it is used for handling numerical operations.
- **uuid_generator**: A custom module imported to generate UUIDs using the function `generate_uuid`.

## 2. Class for Storing Details of All Search Results (`SearchResult`)

A class `SearchResult` is defined, inheriting from `BaseModel`. This class represents a model for storing and validating the details of a video search result. The class contains the following attributes:

- **uuid**: A unique identifier for the search result (64-bit integer).
- **video_title**: The title of the video (string).
- **video_id**: The unique ID of the video (string).
- **video_url**: The URL of the video (HTTP URL).
- **video_view_count**: The number of views the video has received (integer).
- **video_date**: The date the video was published (string).
- **video_likes**: The number of likes the video has received (integer).
- **channel_url**: The URL of the channel that uploaded the video (HTTP URL).
- **video_number_of_subscribers**: The number of subscribers of the channel (integer).
- **video_duration**: The duration of the video (integer, likely in seconds).
- **video_subtitles_available**: A boolean indicating whether subtitles are available for the video.
- **video_published_date**: The date the video was published (string).
- **video_description**: A brief description of the video (string, optional, and can be `None`).

## 3. Example Usage

### UUID Generation

A unique UUID is generated by combining a datetime string with a custom UUID generation function.

### Data Dictionary

An example dictionary `search_result_data` is provided, containing details about a specific video.

### Creating an Instance

An instance of `SearchResult` is created using the `**` operator to unpack the `search_result_data` dictionary into the class.

### Converting to JSON

The instance is then converted to a JSON string using the `.json()` method.

### Parsing from JSON

The JSON string is parsed back into a `SearchResult` instance using the `parse_raw` method.

## Demonstration

The code demonstrates how to define a data model using `pydantic` to validate and manage video search results. It shows the following steps:

- Generating a UUID.
- Creating an instance of the model.
- Serializing it to JSON.
- Deserializing it back into a Python object.

### Code Example

```python
from pydantic import BaseModel, Field, HttpUrl 
import datetime
import numpy as np
from uuid_generator import generate_uuid

class SearchResult(BaseModel):
    type: str = "SearchResult"
    uuid: np.int64
    video_title: str
    video_id: str
    video_url: HttpUrl
    video_view_count: int
    video_date: str
    video_likes: int
    channel_url: HttpUrl
    video_duration: int
    video_number_of_subscribers: int
    video_subtitles_available: bool = False
    video_published_date: str
    video_description: str = None

# Example usage
uuid = np.int64(generate_uuid(datetime.datetime.now().strftime("%Y-%m-%dT%H:%M:%S.&f")))
search_result_data = {
    "uuid": uuid,
    "video_title": "Web Scraping vs Web Crawling Explained",
    "video_id": "TLosoD249NA",
    "video_url": "https://www.youtube.com/watch?v=TLosoD249NA", 
    "video_view_count": 31942,
    "video_date": "2020-06-24T00:00:00.000Z",
    "video_likes": 477,
    "channel_url": "https://www.youtube.com/@zytedata",
    "video_number_of_subscribers": 3798,
    "video_duration": "00:03:14",
    "video_subtitles_available": True,
    "video_published_date": "2020-06-20T00:00:00.000Z",
    "video_description": "An explanation of the differences between web scraping and web crawling."
}

# Create an instance of SearchResult
search_result = SearchResult(**search_result_data)

# Convert to JSON
json_str = search_result.json()
print(json_str)

# Parse from JSON
parsed_result = SearchResult.parse_raw(json_str)
print(parsed_result)
```
# VideoPageData

This Python code snippet utilizes the `pydantic` library to create a data model called `VideoPageData`. Below is a detailed explanation of the code:

## 1. Importing Dependencies

The following libraries and modules are imported:

- **BaseModel, Field, ValidationError, and validator**: Imported from `pydantic`, used for creating and validating the data model.
- **List and Optional**: Imported from `typing` for type annotations.
- **datetime**: Used for handling date and time operations.
- **numpy**: Imported as `np`, used for numerical operations.
- **uuid_generator**: A custom module used to generate UUIDs via a function `generate_uuid`.

## 2. Class for Storing All Information on the Video Page (`VideoPageData`)

A class `VideoPageData` is defined, inheriting from `BaseModel`. This class represents a model for storing and validating detailed information about a video page. The class includes the following attributes:

- **uuid**: A unique identifier for the video page (64-bit integer).
- **video_id**: The unique ID of the video (string).
- **video_url**: The URL of the video (string).
- **video_title**: The title of the video (string).
- **video_thumbnail**: The URL of the video’s thumbnail (string).
- **video_description**: A brief description of the video (string).
- **channel_id**: The ID of the channel that uploaded the video (string).
- **video_resolutions**: A list of available video resolutions (list of strings).
- **video_metadata**: A dictionary containing additional metadata about the video (dictionary).
- **video_scraped**: A boolean indicating if the video data has been scraped.
- **video_published_date**: The date the video was published (string).
- **video_data_field**: An optional field for storing additional video-related data (optional list of strings).

## 3. Example Usage

### UUID Generation

A unique UUID is generated by combining a datetime string with a custom UUID generation function.

### Data Dictionary

An example dictionary `video_data` is provided, containing comprehensive details about a specific video, including its resolutions and metadata.

### Creating an Instance

An instance of `VideoPageData` is created using the `**` operator to unpack the `video_data` dictionary into the class.

### Converting to JSON

The instance is then serialized to a JSON string using the `.json()` method.

### Parsing from JSON

The JSON string is parsed back into a `VideoPageData` instance using the `parse_raw` method.

## Summary

This example demonstrates how to define a more complex data model using `pydantic` to manage detailed information about a video page. The model includes multiple fields, some of which are optional or contain lists or dictionaries. The code shows how to generate a UUID, create an instance of the model with detailed video data, serialize it to JSON, and then deserialize it back into a Python object.

### Code Example

```python
from pydantic import BaseModel, Field, ValidationError, validator
import datetime
import numpy as np
from typing import List, Optional
from uuid_generator import generate_uuid

class VideoPageData(BaseModel):
    type: str = "VideoPageData"
    uuid: np.int64
    video_id: str
    video_url: str
    video_title: str
    video_thumbnail: str
    video_description: str
    channel_id: str
    video_resolutions: List[str]
    video_metadata: dict
    video_scraped: bool
    video_published_date: str
    video_data_field: Optional[str]

# Example usage
uuid = np.int64(generate_uuid(datetime.datetime.now().strftime("%Y-%m-%dT%H:%M:%S.&f")))
video_data = {
    "uuid": uuid,
    "video_id": "KaXJDKCvbHY",
    "video_url": "https://youtu.be/KaXJDKCvbHY",
    "video_title": "Sample Video",
    "video_thumbnail": "http://example.com/thumbnail.jpg",
    "video_description": "This is a sample video description.",
    "channel_id": "channel123",
    "video_resolutions": ["1080p", "720p"],
    "video_metadata": {
        "views": 1000,
        "likes": 100,
        "dislikes": 10,
        "publishedAt": "2023-01-01T00:00:00Z",
        "duration": "00:03:14"
    },
    "video_scraped": True,
    "video_published_date": "2023-01-01T12:00:00Z",
    "video_data_field": "additional data"
}

# Create an instance of VideoPageData
video_page_data = VideoPageData(**video_data)

# Convert to JSON
json_str = video_page_data.json()
print(json_str)

# Parse from JSON
parsed_data = VideoPageData.parse_raw(json_str)
print(parsed_data)
```
# ChannelVideo

This Python script defines a simple data model called `ChannelVideo` using the `pydantic` library. Below is a detailed explanation of the code.

## Code Overview

### Importing Dependencies

The following libraries and modules are imported:

- **BaseModel and Field**: Imported from `pydantic`, used for creating and validating the data model.
- **datetime**: Used for working with date and time operations.
- **numpy**: Imported as `np`, used for numerical operations.
- **uuid_generator**: A custom module used to generate UUIDs via the function `generate_uuid`.

### Class Definition: `ChannelVideo`

The `ChannelVideo` class inherits from `BaseModel`. This class represents a model for associating a video with a specific channel. The class includes the following attributes:

- **uuid**: A unique identifier for the channel-video association (64-bit integer).
- **channel_uuid**: The UUID of the channel (64-bit integer).
- **video_uuid**: The UUID of the video (64-bit integer).

### Example Usage

#### UUID Generation

Two unique UUIDs are generated, one for the channel and one for the video, using a custom UUID generation function combined with the current datetime.

## Code Example

```python
from pydantic import BaseModel, Field
import datetime
import numpy as np
from uuid_generator import generate_uuid

class ChannelVideo(BaseModel):
    type: str = "ChannelVideo"
    uuid: np.int64
    channel_uuid: int
    video_uuid: int

# Example usage
channel_uuid = np.int64(generate_uuid(datetime.datetime.now().strftime("%Y-%m-%dT%H:%M:%S.%f")))
video_uuid = np.int64(generate_uuid(datetime.datetime.now().strftime("%Y-%m-%dT%H:%M:%S.%f")))

channel_video_data = {
    "channel_uuid": channel_uuid,
    "video_uuid": video_uuid,
}

# Create an instance of ChannelVideo
channel_video = ChannelVideo(**channel_video_data)

# Convert to JSON
json_str = channel_video.json()
print(json_str)

# Parse from JSON
parsed_channel_video = ChannelVideo.parse_raw(json_str)
print(parsed_channel_video)
```
# Channel

This Python script defines a data model called `Channel` using the `pydantic` library, which is useful for data validation and settings management. Below is a detailed breakdown of the code.

## Code Overview

### Importing Necessary Dependencies

The following libraries and modules are imported:

- **BaseModel, Field, and HttpUrl**: Imported from `pydantic` for defining and validating data models. `BaseModel` serves as the base class, `Field` is used for setting default values and validation rules, and `HttpUrl` is a specialized field type for validating URLs.
- **datetime**: Used for handling date and time operations, particularly when generating a unique identifier (UUID).
- **numpy**: Imported as `np`, used for numerical operations, specifically to ensure the UUID is treated as a 64-bit integer.
- **generate_uuid**: A custom function imported from the `uuid_generator` module, used to generate a UUID based on the current date and time.

### Class Definition: `Channel`

The `Channel` class inherits from `BaseModel`. This class serves as a model for storing and validating information about a channel. The class includes the following attributes:

- **type**: A string with a default value of "Channel", indicating the type of the object.
- **uuid**: A unique identifier for the channel, stored as a 64-bit integer (`np.int64`).
- **channel_url**: The URL of the channel, validated as a valid URL using the `HttpUrl` type.

### Example Usage

#### UUID Generation

A unique UUID is generated by combining the current date and time (formatted as a string) with the custom `generate_uuid` function. This UUID is then converted to a 64-bit integer.

## Code Example
```python
from pydantic import BaseModel, Field, HttpUrl
import datetime
import numpy as np
from uuid_generator import generate_uuid

class Channel(BaseModel):
    type: str = "Channel"
    uuid: np.int64
    channel_url: HttpUrl

# Example usage
uuid = np.int64(generate_uuid(datetime.datetime.now().strftime("%Y-%m-%dT%H:%M:%S.%f")))
channel_data = {
    "uuid": uuid,
    "channel_url": "https://www.youtube.com/@zytedata",
}

# Create an instance of Channel
channel = Channel(**channel_data)

# Convert to JSON
json_str = channel.json()
print(json_str)

# Parse from JSON
parsed_channel = Channel.parse_raw(json_str)
print(parsed_channel)
```

# VideoPage

This Python script defines a data model called `VideoPage` using the `pydantic` library, which is useful for data validation and settings management. Below is a detailed breakdown of the code.

## Code Overview

### Importing Necessary Dependencies

The following libraries and modules are imported:

- **BaseModel, Field, and HttpUrl**: Imported from `pydantic` for defining and validating data models. `BaseModel` serves as the base class, `Field` is used for defining fields with validation rules, and `HttpUrl` is a specialized field type that ensures the value is a valid URL.
- **datetime**: Used for working with date and time, particularly useful when generating unique identifiers (UUIDs).
- **numpy**: Imported as `np`, a library for numerical operations, specifically to handle the UUID as a 64-bit integer.
- **generate_uuid**: A custom function imported from the `uuid_generator` module, used to generate a unique identifier based on the current date and time.

### Class Definition: `VideoPage`

The `VideoPage` class inherits from `BaseModel`. This class serves as a model for storing and validating the essential information related to a video page. The class includes the following attributes:

- **type**: A string with a default value of "VideoPage", indicating the type of the object.
- **uuid**: A unique identifier for the video page, stored as a 64-bit integer (`np.int64`).
- **video_url**: The URL of the video, validated as a proper URL using the `HttpUrl` type.

### Example Usage

#### UUID Generation

A unique UUID is generated by combining the current date and time (formatted as a string) with the custom `generate_uuid` function. This UUID is then converted to a 64-bit integer.

## Code Example
```python
from pydantic import BaseModel, Field, HttpUrl
import datetime
import numpy as np
from uuid_generator import generate_uuid

class VideoPage(BaseModel):
    type: str = "VideoPage"
    uuid: np.int64
    video_url: HttpUrl

# Example usage
uuid = np.int64(generate_uuid(datetime.datetime.now().strftime("%Y-%m-%dT%H:%M:%S.%f")))
video_page = {
    "uuid": uuid,
    "video_url": "https://www.youtube.com/watch?v=TLosoD249NA",
}

# Create an instance of VideoPage
video_page = VideoPage(**video_page)

# Convert to JSON
json_str = video_page.json()
print(json_str)

# Parse from JSON
parsed_video_page = VideoPage.parse_raw(json_str)
print(parsed_video_page)
```

# Uuid64

The `Uuid64` class is a Python implementation designed to generate and manipulate 64-bit UUIDs based on date and time. Below is a detailed explanation of the class and its methods:

## Class (Uuid64)

The `Uuid64` class handles the creation and management of a 64-bit UUID. The class contains various methods for initializing, formatting, and converting the UUID.

### Initialization (`__init__` Method)

```python
def __init__(self):
```

- This is the constructor method that initializes an instance of `Uuid64`.
- `self._value: int = 0`: A private attribute `_value` is initialized to 0. This will later hold the 64-bit UUID.
- `self._create_value_with_date(datetime.now(timezone.utc))`: This method is called during initialization to create a UUID based on the current UTC date and time.

### String Representation (`__str__` Method)

```python
def __str__(self):
```

- This method returns a string representation of the UUID in a typical UUID format.
- The `_value` is converted to a hexadecimal string and then divided into chunks separated by hyphens to follow the UUID format (e.g., `123e4567-e89b-12d3-a456-426614174000`).

### Static Method: `from_date_string`

```python
@staticmethod
def from_date_string(date: str, date_formats: List[str]):
```

- This method creates a `Uuid64` instance from a date string using one of the provided date formats.
- **Date Parsing**: It tries to parse the date string using each format in `date_formats`. If successful, the date is converted to a datetime object.
- **Instance Creation**: A new `Uuid64` instance is created, and the `_create_value_with_date` method is called with the parsed date to generate the UUID.

### Static Method: `from_mongo_value`

```python
@staticmethod
def from_mongo_value(value: int):
```

- This method creates a `Uuid64` instance from a 64-bit integer value (commonly used in MongoDB).
- **Validation**: It checks if the provided value is valid by comparing it to a predefined threshold (`18446744073709551615`). If not valid, it raises a `ValueError`.
- **Instance Creation**: A new `Uuid64` instance is created, and its `_value` is set to the provided integer.

### Conversion to MongoDB Value (`to_mongo_value` Method)

```python
def to_mongo_value(self):
```

- This method returns the UUID value as an integer, suitable for storing in MongoDB.

### Formatted String Conversion (`to_formatted_str` Method)

```python
def to_formatted_str(self):
```

- This method returns the UUID as a formatted string, similar to what the `__str__` method does.

### Creating Value with Date (`_create_value_with_date` Method)

```python
def _create_value_with_date(self, date_value: datetime):
```

- This method generates the 64-bit UUID using the provided date.
- **POSIX Time**: The timestamp of the date is converted into a 32-bit unsigned integer.
- **Random Number Generation**: A secure 32-bit random number is generated.
- **UUID Composition**: The final 64-bit UUID is composed by combining the 32-bit time value and the 32-bit random number.

## Summary

The `Uuid64` class is a custom implementation for generating and manipulating 64-bit UUIDs based on date and time. It allows for creating UUIDs from the current time, a specific date string, or a MongoDB value. The class also provides methods for converting the UUID to a string format and a MongoDB-compatible integer format. This implementation is useful in systems where a compact and time-based unique identifier is required.


### Code Example
```python
import secrets
from datetime import datetime, timezone
from typing import List

class Uuid64:
    _value: int = 0

    def __init__(self):
        # Create with the current UTC date.
        self._create_value_with_date(datetime.now(timezone.utc))

    def __str__(self):
        hex_string = self._value.to_bytes(8, 'big').hex()
        return (hex_string[0:4] + '-' + hex_string[4:8] + '-' + hex_string[8:12] + '-' + hex_string[12:16]).upper()

    @staticmethod
    def from_date_string(date: str, date_formats: List[str]):
        if not date_formats:
            raise ValueError(f"date_formats must include at least one format")
        for fmt in date_formats:
            try:
                date_value = datetime.strptime(date, fmt)
                break
            except ValueError:
                continue
        else:
            raise ValueError(f"time data '{date}' does not match any of the provided formats")
        instance = Uuid64()
        instance._create_value_with_date(date_value)
        return instance

    @staticmethod
    def from_mongo_value(value: int):
        if value < 0 or value > 18446744073709551615:
            raise ValueError(f"the value is not a valid uuid")
        instance = Uuid64()
        instance._value = value
        return instance

    def to_mongo_value(self):
        return self._value

    def to_formatted_str(self):
        return str(self)

    def _create_value_with_date(self, date_value: datetime):
        unix_time_32bit = int(date_value.timestamp()) & 0xFFFFFFFF
        random_32bit = int(secrets.randbits(32)) & 0xFFFFFFFF
        self._value = (random_32bit & 0xFFFFFFFF) | (unix_time_32bit << 32)
```