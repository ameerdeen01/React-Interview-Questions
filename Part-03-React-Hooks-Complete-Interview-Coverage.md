Part 3: React Hooks – Complete Interview Coverage
High priority for experienced React interviews
7. Rules of Hooks
181. What are React Hooks?
182. Why were Hooks introduced?
183. What are the Rules of Hooks?
184. Why should Hooks be called at the top level?
185. Why can't Hooks be called inside conditions?
186. Why can't Hooks be called inside loops?
187. Can Hooks be called inside event handlers?
188. Can Hooks be called inside regular JavaScript functions?
189. Can Hooks be called inside custom Hooks?
190. How does React identify Hooks between renders?
191. What happens if the order of Hooks changes?
192. What is the difference between a built-in Hook and a custom Hook?
193. What is the difference between a Hook and a normal function?
194. What is the eslint-plugin-react-hooks?
195. How does the Rules of Hooks linting work?
8. useState
196. What is useState?
197. What is the syntax of useState?
198. How does useState work internally?
199. What is lazy initialization in useState?
200. What is the difference between useState(0) and useState(() => 0)?
201. How do you update a state variable?
202. How do you update an object in state?
203. How do you update an array in state?
204. Why should state be immutable?
205. How do you update nested objects?
206. How do you update a particular object in an array?
207. How do you remove an item from an array in state?
208. How do you add an item to an array in state?
209. How do you toggle a boolean state?
210. How do you increment a counter?
211. What is a functional state updater?
212. What is the difference between setCount(count + 1) and setCount(prev => prev + 1)?
213. What happens when setState is called multiple times in one event handler?
214. What is automatic batching?
215. How does React 18 automatic batching work?
216. What is a state snapshot?
217. Why does state appear unchanged immediately after calling a setter?
218. What is stale state?
219. How do you solve stale state problems?
220. When should you use useState versus useReducer?
9. useEffect
221. What is useEffect?
222. Why do we use useEffect?
223. What is the syntax of useEffect?
224. What happens when useEffect has no dependency array?
225. What happens when useEffect has an empty dependency array?
226. What happens when useEffect has dependencies?
227. What is the dependency array?
228. How does React compare dependencies?
229. What is the purpose of the cleanup function?
230. When does the cleanup function execute?
231. Does cleanup execute before every effect execution?
232. Does cleanup execute during component unmounting?
233. How do you fetch API data using useEffect?
234. How do you prevent memory leaks in useEffect?
235. How do you cancel an API request in useEffect?
236. What is AbortController?
237. How do you avoid race conditions in API calls?
238. What is an infinite loop in useEffect?
239. Why does an object dependency cause repeated execution?
240. Why does a function dependency cause repeated execution?
241. What are missing dependencies?
242. What is the exhaustive-deps rule?
243. How do you solve stale closures in useEffect?
244. What is the difference between useEffect and lifecycle methods?
245. What is the difference between useEffect and event handlers?
246. When should you NOT use useEffect?
247. Can you update state inside useEffect?
248. How do you subscribe to WebSocket events using useEffect?
249. How do you add and remove event listeners using useEffect?
250. How do you implement polling using useEffect?
251. How do you implement a timer using useEffect?
252. How do you synchronize an external system with React?
253. What happens if the effect returns a Promise?
254. What is the difference between useEffect(() => {}) and useEffect(() => {}, [])?
255. How does Strict Mode affect useEffect?
10. useLayoutEffect and useInsertionEffect
256. What is useLayoutEffect?
257. What is the difference between useEffect and useLayoutEffect?
258. When should you use useLayoutEffect?
259. Does useLayoutEffect run before browser paint?
260. What are the performance implications of useLayoutEffect?
261. How do you measure an element's dimensions using useLayoutEffect?
262. What is useInsertionEffect?
263. What is the purpose of useInsertionEffect?
264. What is the difference between useInsertionEffect and useLayoutEffect?
265. Why is useInsertionEffect mainly used by CSS-in-JS libraries?
11. useMemo
266. What is useMemo?
267. What is the syntax of useMemo?
268. Why do we use useMemo?
269. What is memoization?
270. How does useMemo work?
271. What is the difference between useMemo and useState?
272. What is the difference between useMemo and useEffect?
273. What is the difference between useMemo and useCallback?
274. When should you use useMemo?
275. When should you avoid useMemo?
276. Can useMemo prevent a component from re-rendering?
277. Does useMemo guarantee that a value will always be cached?
278. How do you memoize an expensive calculation?
279. How do you memoize filtered data?
280. How do you use useMemo with React.memo?
12. useCallback
281. What is useCallback?
282. What is the syntax of useCallback?
283. Why do we use useCallback?
284. What is the difference between useCallback and useMemo?
285. What is the difference between useCallback and a normal function?
286. How does useCallback help React.memo?
287. Can useCallback prevent a parent component from re-rendering?
288. When should you use useCallback?
289. When should you avoid useCallback?
290. What is a stale closure in useCallback?
291. How do you solve stale closures in useCallback?
292. What happens when the dependency array is empty?
293. What happens when dependencies change?
294. Can you use useCallback for API calls?
295. What is the difference between memoizing a value and memoizing a function?
13. useRef
296. What is useRef?
297. What is the syntax of useRef?
298. What is the difference between useRef and useState?
299. Does updating a ref cause a re-render?
300. What is the purpose of the .current property?
301. How do you access a DOM element using useRef?
302. How do you focus an input using useRef?
303. How do you store a timer ID using useRef?
304. How do you store previous state using useRef?
305. How do you store mutable values without triggering rendering?
306. What is the difference between createRef and useRef?
307. What is the difference between a callback ref and an object ref?
308. What is forwardRef?
309. Is forwardRef necessary in React 19?
310. What is useImperativeHandle?
311. When should you use useImperativeHandle?
312. How do you expose a child component's methods to a parent?
313. What are the limitations of refs?
314. Why should refs not be used for values that affect UI?
14. useContext
315. What is Context API?
316. Why was Context API introduced?
317. What is createContext?
318. What is useContext?
319. How do you create a Context Provider?
320. How do you consume Context?
321. What is prop drilling?
322. How does Context API solve prop drilling?
323. What is the difference between Context API and Redux?
324. What is the difference between Context API and props?
325. Does Context cause re-renders?
326. How do you optimize Context performance?
327. How do you split Context into multiple contexts?
328. What is the difference between Context and a global state management library?
329. How do you use Context for authentication?
330. How do you use Context for themes?
331. What are the limitations of Context API?
332. Can Context replace Redux?
333. How do you prevent unnecessary Context updates?
15. useReducer
334. What is useReducer?
335. What is the syntax of useReducer?
336. What is a reducer function?
337. What are the arguments of a reducer?
338. What is the difference between useState and useReducer?
339. When should you use useReducer?
340. What is an action in a reducer?
341. What is a dispatch function?
342. What is the difference between dispatch and setState?
343. Can a reducer perform API calls?
344. Why should reducers be pure functions?
345. How do you manage complex state using useReducer?
346. What is lazy initialization in useReducer?
347. How do you combine Context API and useReducer?
348. How do you implement a shopping cart using useReducer?
349. How do you implement authentication state using useReducer?
350. How do you handle multiple actions in a reducer?
16. Custom Hooks
351. What is a custom Hook?
352. Why do we need custom Hooks?
353. What are the naming conventions for custom Hooks?
354. How do you create a custom Hook?
355. What is the difference between a custom Hook and a component?
356. Do custom Hooks share state between components?
357. How do custom Hooks share logic?
358. How do you create a custom useFetch Hook?
359. How do you create a custom useDebounce Hook?
360. How do you create a custom useLocalStorage Hook?
361. How do you create a custom usePrevious Hook?
362. How do you create a custom useWindowSize Hook?
363. How do you create a custom useOutsideClick Hook?
364. How do you create a custom useOnlineStatus Hook?
365. How do you create a custom useAuth Hook?
366. How do you test custom Hooks?
367. What are the limitations of custom Hooks?
368. How do you avoid unnecessary re-renders in custom Hooks?
369. What is the difference between custom Hooks and HOCs?
370. Can one custom Hook call another custom Hook?
17. Other and Advanced React Hooks
371. What is useTransition?
372. What is the difference between useTransition and useDeferredValue?
373. What is a transition in React?
374. What is a non-urgent update?
375. How does useTransition improve UI responsiveness?
376. What is startTransition?
377. What is the difference between startTransition and useTransition?
378. What is useDeferredValue?
379. How does useDeferredValue work?
380. Is useDeferredValue equivalent to debounce?
381. What is useId?
382. How does useId help accessibility?
383. Can useId be used as a list key?
384. What is useSyncExternalStore?
385. When should you use useSyncExternalStore?
386. What is tearing in React?
387. How does useSyncExternalStore prevent tearing?
388. What is useDebugValue?
389. What is useEffectEvent?
390. When should you use useEffectEvent?
391. What is the use API?
392. How is use different from other Hooks?
393. Can use be called conditionally?
394. How does use read a Promise?
395. How does use work with Suspense?
396. What is useActionState?
397. What is useOptimistic?
398. What is useFormStatus?
399. What is the difference between useActionState and useState?
400. What is the difference between useOptimistic and regular state?
