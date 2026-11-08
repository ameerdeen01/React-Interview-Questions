Part 2: React Rendering, Virtual DOM and Reconciliation
4. Virtual DOM and React Fiber
101. What is the Virtual DOM?
102. How does the Virtual DOM work?
103. How does React create a Virtual DOM?
104. What is the difference between Virtual DOM and Shadow DOM?
105. Is Virtual DOM faster than the Real DOM?
106. How does React minimize DOM operations?
107. What is the diffing algorithm?
108. What is reconciliation?
109. What is React Fiber?
110. Why was Fiber introduced?
111. What are the main responsibilities of Fiber?
112. What is the Fiber node?
113. What is the difference between the current Fiber tree and work-in-progress Fiber tree?
114. What is the render phase?
115. What is the commit phase?
116. What happens during the render phase?
117. What happens during the commit phase?
118. Can the render phase be interrupted?
119. Can the commit phase be interrupted?
120. What is concurrent rendering?
121. What is time slicing?
122. What is cooperative scheduling?
123. How does React prioritize updates?
124. What is the Scheduler in React?
125. What is the difference between synchronous and concurrent rendering?
126. What are lanes in React Fiber?
127. What is the purpose of the lane model?
128. What is an update queue?
129. What is a Fiber effect?
130. What is the difference between a React render and a DOM update?
5. React Rendering Behavior
131. What causes a React component to re-render?
132. Does a parent re-render cause its children to re-render?
133. Does changing props cause a re-render?
134. Does changing state cause a re-render?
135. Does changing context cause a re-render?
136. Does changing a ref cause a re-render?
137. Does changing a normal variable cause a re-render?
138. What is the difference between rendering and mounting?
139. What is the difference between re-rendering and remounting?
140. What is a component lifecycle?
141. What are the lifecycle methods in class components?
142. What is componentDidMount?
143. What is componentDidUpdate?
144. What is componentWillUnmount?
145. What is getDerivedStateFromProps?
146. What is getSnapshotBeforeUpdate?
147. What is shouldComponentUpdate?
148. What is componentDidCatch?
149. What is getDerivedStateFromError?
150. What is the equivalent of lifecycle methods using hooks?
151. What is the difference between mounting and unmounting?
152. Why does React Strict Mode render components twice in development?
153. Does Strict Mode double-render in production?
154. Why does useEffect execute twice in development?
155. How do you prevent unnecessary rendering?
156. What is a render cascade?
157. What is cascading state update?
158. What is a render loop?
159. How do you identify infinite rendering?
160. How do you debug unexpected re-renders?
6. Keys and Lists
161. What is the purpose of the key prop?
162. Why are keys important in React?
163. Why should keys be unique?
164. Why should we avoid using array indexes as keys?
165. When is using the array index as a key acceptable?
166. What happens when keys are missing?
167. What happens when keys are duplicated?
168. How does React use keys during reconciliation?
169. How do keys help preserve component state?
170. How can keys reset component state?
171. What happens when a list is reordered?
172. What is the difference between stable keys and dynamic keys?
173. Why should random values not be used as keys?
174. How do you render a list of objects?
175. How do you render nested lists?
176. How do you render a list with conditional elements?
177. How do you optimize a large list?
178. What is list virtualization?
179. What is windowing?
180. What is the difference between map() and forEach() in React rendering?
