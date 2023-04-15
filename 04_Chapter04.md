# Chapter 4: Orientation and Induction

Thus far, we have explored the various aspects of preparing for your first day at work. From setting goals and objectives to honing your skill set, we have covered everything you need to succeed. But now that the big day is here, it's time to take the next step and familiarize yourself with the company and its culture. It's time for Orientation and Induction.

In this chapter, we will delve into the importance of Orientation and Induction and how it can set you up for success. We’ll explore the process of onboarding, which is essential for learning the ropes and acclimating to new organizational cultures. Moreover, we’ll focus on how to get the most from your Orientation and Induction and how to make the most of it.

Onboarding can come in different formats, and you may experience diverse approaches, depending on the firm's structure and environment. Your company's Human Resources department will likely lead Orientation, plus it may vary from formal classroom training to job shadowing, mentoring, or a self-guided tour of the office.

Offering an ideal onboarding experience is critical because employee orientation is a vital component of the retention and productivity strategies of any robust company. It can create a positive first impression and facilitate trust and loyalty that can last a lifetime.

Therefore, it's essential to pay attention to every detail and follow every guideline handed to you. To make that easy, we will help you navigate the first few days of your new job and ensure you make a great first impression. So, let's dive into the deep end and get started with Orientation and Induction!
# The Tale of The New Hire's Odyssey

In the land of West Africa, the story of the new hire's Odyssey had been told for generations. It was a tale of a young hero named Ndubisi, who sought to make his mark in the world. Ndubisi had heard tales of a great company that he could work for, and nothing could stop him from following his dreams. 

Ndubisi embarked on his Odyssey, armed with his skills and determination, and as he reached the gates of the great company, he gazed in awe at the towering skyscraper. He took a deep breath and walked through the doors, where he was met by the wise old gatekeeper, Nneka.

Nneka welcomed Ndubisi and led him towards the heart of the company, where the Orientation and Induction process would take place. She taught Ndubisi the ways of the company, its culture, and its values. Ndubisi was given a tour of the sprawling office, and he met the key players, who told him what was expected of him in this new world.

Ndubisi was grateful for the guidance he received, for he knew that it would be invaluable as he embarked on his exciting journey. The induction process ensured that he was well-equipped to tackle any task thrown his way.

Ndubisi marveled at how the company prepared its new hires to succeed in the business world. He knew that with their guidance, he could become the hero he always knew he could be. 

As he completed his Orientation and Induction, Ndubisi knew that he was ready to embark on the journey of a lifetime. With his newfound knowledge, he set out to accomplish everything he had set his mind to. 

And thus, Ndubisi's Odyssey came full circle; he had finally found his place in the world, all thanks to the company that gave him a chance to pave his path towards success.
In the story of Ndubisi's Odyssey, we witnessed the crucial role played by the Orientation and Induction process. In real life too, for new employees, an onboarding process acts the same- a crucial role in preparing them for their journey within their organization.

To facilitate the Orientation and Induction of new employees efficiently, many organizations today often use various technologies to streamline the process and create customized welcome packs that include company values, training modules, and vital paperwork.

For instance, an HR software called "DayOne,"  which specializes in employee onboarding, offers a platform for businesses to create, share, and manage interactive onboarding processes and employee induction plans. Organizations can use this DayOne software to create their custom induction plan and create a seamless process that educates the new hires about the company's corporate culture, values, vision, and policies. 

Using the software’s APIs, businesses can integrate third-party HR applications with their onboarding process to make the entire process more efficient and effective.

To integrate the DayOne API into your organization's HR software, you can use the following code snippet, which outlines the basic HTTP request used to call the API:

```
const { API_KEY } = process.env;
const BASE_URL = "https://dayonehr.com/api/v1/";

const authorizeHeaders = {
    "Authorization": `Bearer ${API_KEY}`,
};

const getOnboardingPlan = async (planId) => {
    const API_URL = `${BASE_URL}/onboarding/plans/${planId}`;
    try {
         const response = await axios.get(API_URL, { headers: authorizeHeaders });
         return response.data;
    } catch (error) {
        console.error(error);
    }
}

const createUser = async (credentials) => {
    const API_URL = `${BASE_URL}/users`;
     try {
        const response = await axios.post(API_URL, credentials , { headers: authorizeHeaders });
         return response.data;
     } catch (error) {
       console.error(error);
     }
}
```

The API call uses Axios, a popular JavaScript library to make HTTP requests, to communicate with the DayOne servers. It also utilizes a RESTful API structure that makes it easy for developers to use.

With the assistance of the DayOne software and a few lines of code, businesses can provide new employees with a dynamic and informative onboarding experience that sets them up for success.


[Next Chapter](05_Chapter05.md)