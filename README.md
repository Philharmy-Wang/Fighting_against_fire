# Fighting against forest fire: A lightweight real-time detection approach for forest fire based on synthetic images

#  Building Datasets in Unreal Engine 5


## 1. Preparing Assets from the Unreal Engine Marketplace

### 1.1 Registration & Login

- If you don't already have an Epic Games account:
  
  - Visit the [Epic Games official website](https://www.epicgames.com/store/en-US/)
    
    ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/2d3516b6-ec30-4d97-b885-96683c14821d)
    
  - Click on "Login" at the top right corner of the page, then choose "Register".
    
    ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/58f396a9-8bcf-4aaf-8450-d4ab7ddcd35a)
    
  - Follow the prompts to enter your details and complete the verification.

### 1.2 Browsing & Searching for Assets

- Open the [Unreal Engine Marketplace](https://www.unrealengine.com/marketplace/en-US/store).
- Type keywords into the search bar, e.g., `forest vegetation`, `fire VFX`, `smoke VFX`.  
- In the search results, you can filter by category, rating, price, etc.
   ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/6c62c129-4148-4154-b46e-e1a3fc421c96)

### 1.3 Selecting Assets

- Carefully inspect each product's:
  - **Image Preview**: Check the asset's details, quality, and style to see if it fits your needs.
    ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/91fa785f-bc25-4e91-881f-0811d0107bf3)
  - **Video Demo**: If provided, it can help you get a better idea of the asset's actual effects.
    ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/501b4837-6441-43c1-b2a0-87040ebdd91c)
  - **User Reviews**: Feedback from other users can provide additional insights about the asset.
    ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/9a62869a-8290-4d64-ac52-360af2b938be)

### 1.4 Purchasing & Downloading

- Click on the asset you've chosen.
- Thoroughly read the product description, technical details, etc.
- Click on the `Purchase` button (for paid assets) or `Get for Free` (for free assets).
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/be9907e1-c432-440d-ba22-bb51526b6769)
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/c76ec82a-9f3b-4485-8517-c45f6e9a49f0)
- After completing the purchase process, the resource will be automatically added to your Epic Games account library.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/6c6c2955-b7c3-4b95-87b0-f8aa345233ba)
- Open the UE5 editor, go to the `Epic Games Launcher` library, locate your asset and select `Add to Project`.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/57bc90ac-fd11-48c4-b636-09bfafcd66fe)

## 2. Scene Layout

### 2.1 Creating a New Scene

- Open the UE5 editor.
  
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/da1188c7-2f6c-4112-b089-7ccd409ee521)

- Go to `File` > `New Level` and choose a basic template, such as "Default" or "VR Basic".
  
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/21bb853a-c34b-43e2-8b97-1c26ea8e8158)

### 2.2 Importing Assets

- Open the `Content Browser`, right-click, and select `Import`.

- Navigate to the directory where you downloaded assets from the Unreal Engine marketplace, and choose the relevant resource files to import.
  
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/876a923f-4e62-4213-8dd5-ca280d611629)


### 2.3 Terrain Construction:

- Select the "Landscape" tool from the left toolbar.
  
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/62cabe52-fd7b-46cf-8f10-01bef3f40334)
  
- In the top settings, adjust the size and resolution of the terrain, then click "Create".
  
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/b5a993f7-e043-4fd2-a5ae-baec36e7f672)
  
- Use the "Sculpt" tool to carve, mimicking the undulations of natural terrain.
- 
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/a74b3727-6687-445c-b09d-11166167847b)


### 2.4 Vegetation Layout:

- Use the `Foliage` tool (usually on the left of the main toolbar) to place and edit vegetation.
  
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/69ca9ca0-c118-46e8-839e-1a2dd37131d9)
  
- In the `Foliage` panel, drag in the vegetation models you want to use.
  
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/0222106b-1fcf-4000-bbbc-85c93f6e6fb8)
  
- Use the brush tool, adjust the brush size and intensity, and paint vegetation onto the terrain.
  
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/05ef6687-f97d-41c3-8fcd-283d33598f84)


### 2.5 Placement of Fires and Smoke:

- In the `Content Browser`, find the effects for flames and smoke (usually .particle files).
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/eb2cde8e-cdbb-40cc-8006-64c9060845a4)
  
- Drag the effects into the scene and place them in the appropriate positions.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/17914bd2-48d9-4913-833f-b76609508c7b)
  
- Use the `Details` panel to adjust the size, direction, intensity, and other properties of the effects.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/5f9a841c-7c7e-4303-bd7e-4b6883b9a348)


### 2.6 Lighting and Camera:

- Add lights using the `Place Actors` panel, such as "Directional Light", "Point Light", etc.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/6791312f-aead-488d-9995-d927507a5115)
  
- Adjust the position, direction, color, and intensity of the lights to simulate different weather and time conditions.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/0675c4f8-f2e6-4ad7-9ec0-feadba8188ae)
  
- Add a `Camera Actor` to the scene to determine the viewpoint and shooting angles.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/23b424e8-c820-466d-89d8-83c2cace489f)
  
- Use the `Details` panel to adjust the camera's focal length, exposure, and other settings.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/739dff1b-9259-4985-af4d-e12b5d9c2fec)

### 2.7 Preview and Save:

- Click the `Play` button to preview the scene in the editor.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/b791d696-78ab-43f1-bff7-3fd2bc817c76)
  
- Adjust the various elements of the scene as needed until satisfied.
- Choose `File` > `Save`, name the scene, and save.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/0d682560-bba2-4e8d-834a-40ae4f8ca318)


## 3 Weather, Time, and Other Details

### 3.1 Setting Up Weather

- **Clear Day**: Adjust the `Directional Light` intensity to simulate sunlight and add `Sky Light` for soft ambient lighting.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/394c973e-8bb5-451c-9bcb-74e787577fd0)
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/9cb15535-884d-4613-8d96-d1250f0556c6)
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/87c11903-c36b-4ba3-bd53-3effed820bbd)

- **Rainy Day**:
  - Use rain effects from the Unreal Engine marketplace or create custom raindrop particle systems.
  - Adjust all the lights in the scene to be dimmer and cooler.
    ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/3c9bbeb7-b272-4dee-8960-fcb2760ea2ab)
  - Consider adding wet surface materials to simulate the ground after rain.

- **Foggy Day**: Use the `Exponential Height Fog` component to simulate fog. Adjust its properties like fog density, color, and distance to mimic different fog effects.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/4f78102a-3765-4990-8469-39be4baedde1)

### 3.2 Adjusting Time

- **Daytime**: Set `Directional Light` to a bright white and ensure the skybox reflects daytime clouds.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/35d16e00-ec2a-466b-a647-fe97eecd9e66)

- **Evening**: Adjust `Directional Light` color to an orange-red hue and decrease its intensity to simulate sunset.
  ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/20dad2ee-d6c5-423b-a2a0-c9d42c2f58df)

- **Nighttime**:
  - Set the `Directional Light` intensity very low and adjust its color to a deep blue.
  - Add `Point Lights` or `Spot Lights` to simulate artificial lighting, such as streetlights or lanterns.
  - Consider adding a skybox texture with stars or a moon.
    ![image](https://github.com/Philharmy-Wang/M4SFWD/assets/51520993/12ae7329-ce82-47f6-993a-303c4138fd33)

### 3.3 Other Details

- **Terrain**: Use the `Landscape` tool to edit the terrain, simulating hills, valleys, or plains. Use different surface materials to distinguish different parts of the ground, like dirt, grass, or rock.
- **Water Bodies**: Add lakes or rivers to the scene, using Unreal Engine's `Water` system or third-party plugins to simulate water flow and reflection.
- **Dynamic Objects**: Consider adding some dynamic objects to enrich the scene, like fluttering leaves, flying birds, or other small animals.
