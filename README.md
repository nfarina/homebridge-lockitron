
# Lockitron Plugin

Example config.json:

    {
      "accessories": [
        {
            "accessory": "Lockitron",
            "name": "Front Door",
            "lock_id": "your-lock-id",
            "api_token" : "your-lockitron-api-access-token"
        }
      ]
    }

This plugin supports Lockitron locks. It uses the Lockitron cloud API, so the Lockitron must be 'awake' for locking and unlocking to actually happen. You can wake up Lockitron after issuing an lock/unlock command by knocking on the door.