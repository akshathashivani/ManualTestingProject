# Social Media App - Manual Testing Scenarios

This document contains **200 high-level functional manual testing scenarios** for a Social Media Application.  



## 1. Username Text Field 

1. To check that the username field is visible.  
2. To check that placeholder text is visible.  
3. To check that input accepts valid characters.  
4. To check that input does not accept empty values.  
5. To check that input does not accept special characters (if restricted).  
6. To check that input supports copy-paste.  
7. To check that input retains value after error.  
8. To check that field is keyboard accessible.  
9. To check that input highlights on focus.  
10. To check that username length restrictions are enforced.  
11. To check input works on mobile devices.  
12. To check input works on desktop devices.  
13. To check input works in dark mode.  
14. To check input works in light mode.  
15. To check field does not overlap with other UI elements.  
16. To check input validation triggers on form submit.  
17. To check input clears when cancel button clicked.  
18. To check field handles rapid typing without issues.  
19. To check error message disappears after valid input.  
20. To check username field works after page refresh.  
21. To check copy-paste of invalid input triggers error.  
22. To check field retains value after navigating back.  
23. To check input truncates correctly if max length exceeded.  
24. To check username displays correctly in profile after login.  
25. To check username field is accessible via screen readers.  

---

## 2. Password Text Field 

26. To check password field is visible.  
27. To check input is masked.  
28. To check placeholder text is visible.  
29. To check field accepts minimum required length.  
30. To check field accepts maximum allowed length.  
31. To check field accepts special characters.  
32. To check copy-paste works.  
33. To check password field validates on submit.  
34. To check error message displays for incorrect password.  
35. To check field retains input after error.  
36. To check password field highlights on focus.  
37. To check field works on mobile.  
38. To check field works on desktop.  
39. To check dark mode compatibility.  
40. To check light mode compatibility.  
41. To check keyboard navigation works.  
42. To check field clears when cancel is clicked.  
43. To check session persists after correct password entry.  
44. To check error disappears after correcting input.  
45. To check field truncates input if max length exceeded.  
46. To check field handles rapid typing without issues.  
47. To check password field triggers tooltip/hint if enabled.  
48. To check password field works after page refresh.  
49. To check field works for OTP password if required.  
50. To check field is accessible via screen readers.  

---

## 3. Login Button 

51. To check login button is visible.  
52. To check login button is disabled when fields are empty.  
53. To check login button is enabled after valid input.  
54. To check clicking login with correct credentials logs in.  
55. To check clicking login with incorrect credentials shows error.  
56. To check login button works on mobile.  
57. To check login button works on desktop.  
58. To check pressing Enter triggers login.  
59. To check login button highlights on focus.  
60. To check double click does not crash app.  
61. To check login button works after OTP verification.  
62. To check login triggers error messages for invalid input.  
63. To check login button is accessible via screen readers.  
64. To check login works on slow network.  
65. To check login success navigates to homepage/dashboard.  

---

## 4. Cancel Button 

66. To check cancel button is visible on login/registration.  
67. To check cancel button clears all input fields.  
68. To check cancel button discards unsaved changes in profile.  
69. To check cancel button does not log out the user.  
70. To check cancel button is accessible via keyboard and screen readers.  

---

## 5. Forgot Password Link 

71. To check forgot password link is visible.  
72. To check clicking link navigates to recovery page.  
73. To check page loads on mobile and desktop.  
74. To check field validations work for email/username input.  
75. To check recovery process completes successfully.  

---

## 6. OTP Field 

76. To check OTP field is visible after login/registration.  
77. To check field accepts numeric input only.  
78. To check resend OTP functionality works.  
79. To check error message displays for invalid OTP.  
80. To check field works on mobile and desktop.  

---

## 7. Register Button 

81. To check register button is visible.  
82. To check button is disabled until mandatory fields are filled.  
83. To check button is enabled after valid input.  
84. To check clicking button creates account successfully.  
85. To check error messages display for invalid input.  
86. To check double click does not crash app.  
87. To check button works on mobile.  
88. To check button works on desktop.  
89. To check button highlights on focus.  
90. To check button is accessible via screen readers.  

---

## 8. Captcha 

91. To check captcha is visible on registration.  
92. To check captcha validation works correctly.  
93. To check error message displays for wrong captcha.  
94. To check captcha refresh works.  
95. To check captcha works on mobile and desktop.  



## 9. Profile Fields 

96. To check profile picture is visible.  
97. To check profile picture can be uploaded/changed.  
98. To check display name is visible and editable.  
99. To check bio field is visible and editable.  
100. To check save button is visible and disabled until changes are made.  
101. To check save button saves changes correctly.  
102. To check cancel button discards changes.  
103. To check profile info reflects correctly across the app.  
104. To check profile page loads on mobile.  
105. To check profile page loads on desktop.  
106. To check focus highlights editable fields.  
107. To check keyboard navigation works in profile.  
108. To check profile fields persist after page reload.  
109. To check profile fields persist after logout/login.  
110. To check error messages appear for invalid input.  
111. To check profile picture maintains aspect ratio.  
112. To check bio character limit enforced.  
113. To check save button triggers success message.  
114. To check cancel button triggers discard confirmation if needed.  
115. To check profile page is accessible via screen readers.
## 10. Post Button 

116. To check the post button is visible on feed.  
117. To check the post button is disabled when no content is entered.  
118. To check the post button is enabled after entering text.  
119. To check clicking post button publishes the post successfully.  
120. To check post button works for image uploads.  
121. To check post button works for video uploads.  
122. To check post button works for combined text + media posts.  
123. To check double-clicking post button does not duplicate the post.  
124. To check post button works on mobile devices.  
125. To check post button works on desktop devices.  
126. To check post button triggers error message for invalid input.  
127. To check post button highlights/focus works correctly.  
128. To check post button is accessible via keyboard navigation.  
129. To check post button is accessible via screen readers.  
130. To check post button works under slow network conditions.  

---

## 11. Media Upload

131. To check media upload button is visible.  
132. To check image upload works successfully.  
133. To check video upload works successfully.  
134. To check unsupported file types show an error.  
135. To check media preview appears before posting.  
136. To check media uploads are reflected in posts correctly.  
137. To check media upload works on mobile devices.  
138. To check media upload works on desktop devices.  
139. To check media upload fails gracefully if network is slow.  
140. To check media upload is accessible via keyboard and screen readers.  

---

## 12. Like Button 

141. To check like button is visible on posts.  
142. To check clicking like button updates like count.  
143. To check unliking a post works correctly.  
144. To check like button works on mobile and desktop.  
145. To check like button is accessible via keyboard and screen readers.  

---

## 13. Comment Button 

146. To check comment button is visible on posts.  
147. To check clicking comment button opens comment input field.  
148. To check adding a comment updates comment count.  
149. To check comment button works on mobile and desktop.  
150. To check comment button is accessible via keyboard and screen readers.  

---

## 14. Share Button

151. To check share button is visible on posts.  
152. To check clicking share button allows sharing to friends/followers.  
153. To check share count updates correctly.  
154. To check share button works on mobile and desktop.  
155. To check share button is accessible via keyboard and screen readers.  

---

## 15. Notification Toggle Buttons 

156. To check notification toggle buttons are visible.  
157. To check toggles enable notifications for likes/comments/messages.  
158. To check toggles disable notifications correctly.  
159. To check toggles persist changes after saving.  
160. To check toggles reflect correctly in notification panel.  
161. To check toggles work on mobile devices.  
162. To check toggles work on desktop devices.  
163. To check toggles are accessible via keyboard.  
164. To check toggles are accessible via screen readers.  
165. To check toggles work under slow network conditions.  

---

## 16. Search Field 

166. To check search field is visible on main page.  
167. To check search accepts valid input only.  
168. To check search suggestions appear as you type.  
169. To check pressing Enter triggers search.  
170. To check search results display correctly.  
171. To check search works on mobile devices.  
172. To check search works on desktop devices.  
173. To check clear search button works correctly.  
174. To check search field retains input after navigating back.  
175. To check search field is accessible via keyboard and screen readers.  

---

## 17. Logout Button 

176. To check logout button is visible in profile/settings.  
177. To check clicking logout successfully logs out the user.  
178. To check user is redirected to login page after logout.  
179. To check logout works on mobile and desktop.  
180. To check logout button is accessible via keyboard and screen readers.  

---

## 18. Chat Input Field 

181. To check chat input field is visible in chat window.  
182. To check field accepts text input.  
183. To check field supports emojis.  
184. To check field supports copy-paste.  
185. To check sending text messages works correctly.  
186. To check sending media in chat works.  
187. To check messages appear in correct order.  
188. To check chat input works on mobile devices.  
189. To check chat input works on desktop devices.  
190. To check chat input is accessible via keyboard and screen readers.  

---

## 19. Chat Send Button 

191. To check send button is visible in chat window.  
192. To check clicking send button sends the message successfully.  
193. To check send button works on mobile devices.  
194. To check send button works on desktop devices.  
195. To check send button is accessible via keyboard and screen readers.  

---

## 20. Settings Toggle & Save Button 

196. To check settings toggle buttons are visible.  
197. To check toggles enable/disable notification preferences correctly.  
198. To check toggles persist after saving.  
199. To check save button saves all modified settings correctly.  
200. To check save button works on mobile devices.  
201. To check save button works on desktop devices.  
202. To check settings page works under slow network conditions.  
203. To check toggles are accessible via keyboard navigation.  
204. To check save button is accessible via screen readers.  
205. To check toggles and save button work in both dark and light modes.  
  


