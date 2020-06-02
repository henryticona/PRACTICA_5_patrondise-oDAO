# PRACTICA_5_patrondise-oDAO

BASE DE DATOS ALMACEN

-- phpMyAdmin SQL Dump
-- version 4.8.5
-- https://www.phpmyadmin.net/
--
-- Servidor: 127.0.0.1
-- Tiempo de generación: 02-06-2020 a las 23:15:26
-- Versión del servidor: 10.1.38-MariaDB
-- Versión de PHP: 7.3.3

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET AUTOCOMMIT = 0;
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Base de datos: `bd_almacen`
--

-- --------------------------------------------------------

--
-- Estructura de tabla para la tabla `productos`
--

CREATE TABLE `productos` (
  `id` int(11) NOT NULL,
  `descripcion` varchar(250) DEFAULT NULL,
  `stock` int(250) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

--
-- Volcado de datos para la tabla `productos`
--

INSERT INTO `productos` (`id`, `descripcion`, `stock`) VALUES
(1, 'Celular Huawei Y9', 110),
(2, 'Laptop HP 5ta Genreacion 1T de disco duro y 32GB de RAM', 70),
(3, 'Router TP-LINK 3 antenas rompemuros', 55),
(4, 'Switch TP-LINK D216 ', 40),
(5, 'Estabilizador OMEGA', 120);

--
-- Índices para tablas volcadas
--

--
-- Indices de la tabla `productos`
--
ALTER TABLE `productos`
  ADD PRIMARY KEY (`id`);

--
-- AUTO_INCREMENT de las tablas volcadas
--

--
-- AUTO_INCREMENT de la tabla `productos`
--
ALTER TABLE `productos`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=6;
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;

BASE DE DATOS
![](Capturas%20de%20Funcionamiento/Base%20de%20Datos.png)

VENTANA DE PRODUCTOS
![](Capturas%20de%20Funcionamiento/Ventana%20de%20PRODUCTOS.png)

VENTANA DE NUEVO REGISTRO
![](Capturas%20de%20Funcionamiento/Ventana%20de%20NUEVO%20REGISTRO.png)

VENTANA PARA EDITAR REGISTRO
![](Capturas%20de%20Funcionamiento/Ventana%20para%20EDITAR%20REGISTRO.png)
