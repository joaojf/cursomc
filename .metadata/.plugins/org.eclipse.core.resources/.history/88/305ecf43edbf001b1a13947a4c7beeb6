package com.cursomc.services;

import java.util.Optional;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Service;

import com.cursomc.domain.Categoria;
import com.cursomc.repositories.CategoriaRepository;

@Service
public class CategoriaService {

	@Autowired
	private CategoriaRepository repositoryCategoria;

	public Categoria buscar(Integer id) {
		Optional<Categoria> obj = repositoryCategoria.findById(id);
		return obj.orElse(null);
	}
}