# gofiber_file_upload_limitation
//two working version ,set the limitation of fiber golang uploading

    app := fiber.New()
    app.Settings.BodyLimit= 100 * 1024 * 1024
  
//another one
  
    app := fiber.New(&fiber.Settings{
    	BodyLimit: 100 * 1024 * 1024, // this is the limit of 100MB
    })
!!
