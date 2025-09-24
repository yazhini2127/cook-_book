Skip to content
Navigation Menu

code Search Results · repo:sanmathielangovan2005-bot/virtual-kitchen language:JavaScript
14 files
in
sanmathielangovan2005-bot/virtual-kitchen(press backspace or delete to remove)


src/App.js
import './App.css';
import Navbar from './components/Navbar';
import Footer from './components/Footer';
import { Route, Routes } from 'react-router-dom';
import Home from './pages/Home';
import Category from './pages/Category';


src/index.js
import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';
import App from './App';
import reportWebVitals from './reportWebVitals';
import { BrowserRouter } from 'react-router-dom';


src/setupTests.js
// jest-dom adds custom jest matchers for asserting on DOM nodes.
// allows you to do things like:
// expect(element).toHaveTextContent(/react/i)
// learn more: https://github.com/testing-library/jest-dom
import '@testing-library/jest-dom';


src/pages/Home.jsx
import React from 'react'
import Hero from '../components/Hero'
import CategoriesHome from '../components/CategoriesHome'
import About from '../components/About'
import NewsLetter from '../components/NewsLetter'
import '../styles/Home.css'


src/pages/Recipie.jsx
import React, { useEffect } from 'react'
import YouTube from 'react-youtube'
import '../styles/Recipie.css'
import { useNavigate, useParams } from 'react-router-dom'
import axios from 'axios'
const Recipie = () => {


src/reportWebVitals.js
const reportWebVitals = onPerfEntry => {
  if (onPerfEntry && onPerfEntry instanceof Function) {
    import('web-vitals').then(({ getCLS, getFID, getFCP, getLCP, getTTFB }) => {
      getCLS(onPerfEntry);
      getFID(onPerfEntry);
      getFCP(onPerfEntry);
      getLCP(onPerfEntry);


src/components/CategoriesHome.jsx
import React, { useEffect } from 'react'
import '../styles/CategoriesHome.css'
import heroImg1 from '../images/hero-img1.png'
import heroImg2 from '../images/hero-img2.png'
import heroImg3 from '../images/hero-img3.png'
import heroImg4 from '../images/hero-img4.png'


src/components/Hero.jsx
import React from 'react'
import '../styles/Hero.css'
import heroImg1 from '../images/hero-img1.png'
import heroImg2 from '../images/hero-img2.png'
import heroImg3 from '../images/hero-img3.png'
import heroImg4 from '../images/hero-img4.png'


src/components/Footer.jsx
import React from 'react'
import '../styles/Footer.css'
import { useNavigate } from 'react-router-dom'
const Footer = () => {
  const navigate = useNavigate()


src/components/NewsLetter.jsx
import React from 'react'
import { IoFastFoodOutline, IoMailOutline } from "react-icons/io5";
import { FaRegCheckCircle } from "react-icons/fa";
import '../styles/NewsLetter.css'
const NewsLetter = () => {


src/components/Navbar.jsx
import React from 'react'
import '../styles/Navbar.css'
import { IoSearch } from "react-icons/io5";
import { Link, useNavigate } from 'react-router-dom'
import axios from 'axios';
const Navbar = () => {


src/components/About.jsx
import React from 'react'
const About = () => {
  return (
    <div>About</div>
  )
}


src/pages/Category.jsx
import React, { useEffect } from 'react'
import '../styles/CategoryPage.css'
import { useNavigate, useParams } from 'react-router-dom';
import axios from 'axios';
const Category = () => {


src/App.test.js
import { render, screen } from '@testing-library/react';
import App from './App';
test('renders learn react link', () => {
  render(<App />);
  const linkElement = screen.getByText(/learn react/i);
  expect(linkElement).toBeInTheDocument();
Code search results
cook book demo link:your virtual kitchen Assistant
https://drive.google.com/file/d/1ccVMDE2OKcFfcbBEH0f6XElXISDYtT5j/view?usp=drivesdk
