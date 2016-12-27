package com.citibridge.cap.controller;


import org.springframework.http.HttpStatus;
import org.springframework.http.MediaType;
import org.springframework.http.ResponseEntity;
import org.springframework.stereotype.Controller;
import org.springframework.web.bind.annotation.ModelAttribute;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RequestMethod;
import org.springframework.web.bind.annotation.ResponseBody;




@Controller
@RequestMapping("/")
public class CAPTRSController {
	
	
	@RequestMapping(value="/validateUser",method=RequestMethod.POST,
			produces="application/json")
	@ResponseBody
	public Object validateUser() throws Exception {
		
		/*System.out.println("Inside validate user");
		System.out.println("User name:"+userInfo.getUserName());
		System.out.println("Password:"+userInfo.getPassword());*/
		
		//validate user info and Send equivalent SUCCESS/FAILURE message.
		return "hello";
	}
	
}